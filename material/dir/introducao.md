# Introdução ao kubernetes

A tecnologia de containers possibilita rodar processos, serviços e aplicativos de 
maneira isolada, ou seja, um não enxerga o outro, de forma limitada, no qual cada um 
possui um limite dos recursos de hardware disponíveis como quantidade de memória e
espaço em disco.

[Kubernetes](https://kubernetes.io/) é uma plataforma Open Source extensivel e portal 
para o gerenciamento de cluster de containeres, desenvolvido pelo Google.
Como características auto-scaling de serviços de containeres, auto-monitoração de
containeres, permite o deploy de containers e serviços, load balancer, orquestração de containers, e
orquestação de volumes de armazenamento 'storeges'.


## Orquestração com Kubernetes

Orquestração de containeres é a capacidade de provisionar automaticamente a 
infraestrutura necessária para etender às solicitações das aplicações web por meio
de containers do Docker.

Kubernetes, também conhecido como k8s, é uma ferramenta open source criada pela 
Google e distribuída em 2014 para automatização de deploys e gerenciamento de
containers. Com ele é possível criar um cluster de containers em clouds privadas ou
públicas (AWS, Goole Cloud, etc).


## Vantagens do Kubernetes:

* Container sempre online: verifica a saúde da aplicação e recria o container se identificar alguma anomalia.
* Descoberta de Serviço: containers recebem um endereço IP e conseguem enxergar um
ao outro por meio de uma rede virtual.
* Crescimento Horizontal: com um simples comando é possivel aumentar o número de 
containers da mesma imagem.
* Rollbacks automáticos: se algo der errado, Kubernetes volta automaticamente à versão
anterior da aplicação.
* Execução em Batcj: permite rodar comandos em batch como containers.

## Recursos do Kubernetes

O kubernetes pussi vários recurso. Pode ser pensando como:

* Uma plataforma de container
* Uma plataforma de microserviços
* Uma plataforma de Cloud e Iot

Kubernetes fornece um ambiente de gerenciamento centrado em contenieres, ele
orquestra containers, rede e armazenamento.
Isso fornece grande parte da simplicaidade da Plataforma como Serviço (PaaS) 
com a flexibilidade da Infraestrutura como Serviço (IaaS), e permiti
a portabilidade entre provedores.

## Kubernetes como plataforma

Mesmo que o kubernete forneça muitas funcionalidades, sempre há novos cenários
que se beneficiam de novos recursos. A orquestração ad hoc é aceitavel inicialmente,
geralmente requer automação robusta. É por isso que o kubernetes também foi 
projetada para servir como uma plataforma para criar um ecossistema de componentes 
e ferramentas para facilitar a implatação.

O plano de controle do Kubernetes é construído sobre as mesmas APIs que estão 
disponíveis para desenvolvedores e usuários. Os usuários podem escrever seus 
próprios controladores, como agendadores, com suas próprias APIs que pode ser
direcionadas por uma ferramenta de linha de comando de propósito geral.

## O que o Kubernetes não é:
O Kubernetes não é um sistema tradicional de PaaS (Platform as a Service) com tudo
incluido. Como o Kubernetes opera do nívle do contêiner, e não no nível do hardware,
ele fornece alguns recursos geralmente aplicáveis comuns às ofertas de PaaS, 
como implantação, dimensionamento, balanceamento de carga, registo e monitoramento.
No entando, o Kubernetes fornece os blocos de contrução para a contrução de plaraformas
de desenvolvedores, mas preserva a escolha do usuário e a flexibilidade onde é importante.

O Kubernetes visa oferecer suporte a uma variedade extremamente diversificada 
de ambiente , inclue stareless, stateful, e ambiente de processamento.

Não importa fazer deploy do seu codigo e não importa fazer build da sua aplicação.
Integração continua, e Distribuição Continua (CI/CD) são detreminados pela cultura e
preferência da organização, bem como pelos requisitos técnicos.


