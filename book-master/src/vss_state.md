# VSS-State

O VSS-State é o responsável pela definição estratégica a ser utilizada durante o jogo.
A partir dos dados de posição informados pelo pacote responsável pela visão computacional, o VSS-State
calcula  qual será a posição de jogo que cada indivíduo deve adotar, qual a velocidade de cada roda 
e qual a posição final esperada para cada indivíduo. O estado dos indivíduos deve ser avaliado em curtos 
espaços de tempos, tentando se aproximar de uma situação em tempo real e afim de dar dinâmica ao jogo.

## Relação com o VSS-Vision
O VSS-State está fortemente relacionado com o [VSS-Vision](vss_vision.md). Por padrão, uma partida
não começa até que o VSS-Vision mande um conjunto de dados informando as respectivas posições de todos os indivíduos 
apresentados no campo.

## Relação com o VSS-Command
O VSS-State recebe o conjunto de dados do [VSS-Vision](vssvision.md), realiza os cálculos necessários,
 define a estratégia a ser utilizada e, finalmente envia os dados de velovidade para cada roda de cada
 de cada robô irá executar.
