# Arquitetura do kubernetes
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:0 orderedList:0 -->

- [O que é no?](#O-que-é-no-?)
- [Estado de um no](#Estado-de-um-no)

<!-- /TOC -->

# O que é no?

Um no pode ser uma maquina virtual ou fisica de trabalho no kubernetes, 
dependendo do cluster. Anteriomente conhecido como minion. 
Cada no tem serviços necessários para executar pods e é 
gerenciando pelo componentes do master. Os serviços em nó 
incluem Docker, Kubelet and kube-proxy.

# Estado de um no
