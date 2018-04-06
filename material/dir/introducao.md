# Introdução à kubernetes

A tecnologia de containers possibilita rodar processos, serviços e aplicativos de 
maneira isolada, ou seja, um não enxerga o outro, de forma limitada, no qual cada um 
possui um limite dos recursos de hardware disponíveis como quantidade de memória e
espaço em disco.

Kubernetes é um sistema Open Source desenvolvido pelo Google para o gerenciamento de cluster de
containeres tendo como características auto-scaling de serviços e containeres, auto-monitoração de
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


