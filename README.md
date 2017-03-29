# MarsRoverT168A

=== Sondas à Marte

Um esquadrão de sondas robores da NASA estão pousando em uma planalto em Marte.

Este planalto, que é curiosamente retangular, deve ser navegado pelas sondas para que suas cameras possam capturar a visão completa do terreno e mandar de volta a Terra.

A posição de uma sonda é representada pela combinação de coordenadas X e Y e uma letra representa um dos quatro pontos cardinais que a sonda está apontando. O planalto é dividido em uma grade para simplificar a navegação. Um exemplo de posição pode ser 0, 0, N que significa que a sonda esta no fundo e mais a esquerda do planalto e virada para o norte. Controle das Sondas(Input)

Para controlar a sonda, a NASA envia uma string de letras. As letras possíveis são L,R e M. As letras L e R fazem a sonda virar 90 graus para esquerda e direita respectivamente sem se mover. A letra M faz a sonda se mover para frente um quadro na grid sem mudar sua direção. Assuma que o quadro diretamente ao norte de (x, y) é (x, y+1).

A primeira linha da string são as coordenadas correspondentes ao limite superior e mais a esquerda do planalto, considera-se que o planalto sempre inicia em (0,0).

O resto da string é informação pertinentes a sonda. Cada sonda tem duas linhas de entrada. A primeira linha informa onde a sonda está e a segunda linha é uma serie de instruções informando como a sonda deve explorar o planalto.

A posição contem dois inteiros e uma letra separada por espaços, correspondendo as coordenadas X e Y e o ponto cardeal que a sonda está apontada.

Cada sonda executara suas instruções separadamente, que significa que a segunda sonda não começará até que a primeira tenha finalizado seu movimento. Resultado da Operação (Output)

O resultado para cada sonda deve ser suas coordenadas finais e para que ponto cardial a sonda está apontando. Test Input: 5 5 1 2 N LMLMLMLMM 3 3 E MMRMMRMRRM

Expected Output: 1 3 N 5 1 E
