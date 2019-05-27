# VSS-Vision em construção...

É o responsável por capturar posições cartesianas dos robôs a partir da imagem da câmera.
O VSS-Vision está dividido em dois módulos, um de calibragem, onde é possível calibrar cores 
e um módulo de jogo, onde seta-se o padrão de cada robô, assim como a cor do time.
 A definição das posições dos robôs são realizadas a partir do rastreamento das cores calibradas.

#### Calibration
- O sistema utiliza como entrada o número de cores a ser ratreada e os seus respectivos códigos em RGB. Finalmente, 
o sistema realiza calculos para rastrear esas cores, sem ser afetados por mudanças na iluminação.


#### Vision
- Ó sistema insere um plano cartesiano ao campo do jogo que está sendo visualizado.

- Após informadas as cores e calibrada a imagem para reconhecimento das mesmas, o sistema identifica os elementos do jogo com base nas cores, calculando suas posições a partir de coordenadas cartesias.
