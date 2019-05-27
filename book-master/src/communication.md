# Comunicação entre projetos

Foram idealizados dois projetos de comunicação que possuem responsabilidades diferentes. 
Estes projetos seriam: Visão, Estado e Comando.

## Visão
O pacote de visão [VSS-Vision](vss_vision.md) é onde será trabalahda toda a parte referente a visão computacional, ou seja,
 onde seram identificados os indivíduos e também suas respectivas posições.

## Estado
O pacote de estado [VSS-State](vss_state.md) carrega informações das posições e orientações de todos os objetos em campo, define a estratégia 
a ser utilizada por cada indivíduo e envia as informações necessárias para o projeto responsável pelo Comando.

## Comando
O pacote de comando [VSS-Command](vss_command.md) carrega informações do motor, led e das velocidades das rodas dos robôs.
