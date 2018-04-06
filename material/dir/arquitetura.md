# Arquitetura do kubernetes
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:0 orderedList:0 -->

- [O que é no?](#O-que-é-no-?)
- [Estado de um no](#Estado-de-um-no)
- [Gestão](#Gestao)

<!-- /TOC -->

## O que é no?

Um no pode ser uma maquina virtual ou fisica de trabalho no kubernetes, 
dependendo do cluster. Anteriomente conhecido como minion. 
Cada no tem serviços necessários para executar pods e é 
gerenciando pelo componentes do master. Os serviços em nó 
incluem Docker, Kubelet and kube-proxy.

## Estado de um no

Um no contém informações de estatus como:

* [Endereço da interface](https://kubernetes.io/docs/concepts/architecture/nodes/#addresses)
    
    O uso desses campos varia dependendo do seu provedor de nuvem ou configuração bare-metal.

    * HostName
    * Ip Externo
    * IP Interno

* [Condição](https://kubernetes.io/docs/concepts/architecture/nodes/#condition)
    
    O campo de condições descreve o status de todos os nós em execução.

* [Capacidade](https://kubernetes.io/docs/concepts/architecture/nodes/#capacity)

    Descreve os recursos disponivel no no: CPU, memorua e número maximo de pods que podem rodar no No.
    
* [Outras informações](https://kubernetes.io/docs/concepts/architecture/nodes/#info)

    Contém informação geral do no, como versão kernel, versão do kubernet (Kubelet e kube-proxy), 
    versão do docker (se você usa) e o nome do sistema operacional.

## Getão
