# Arquitetura do kubernetes

    - [O que é no?](#O-que-é-no-?)
    - [Estado de um no](#Estado-de-um-no)

# O que é no?

Um no pode ser uma maquina virtual ou fisica de trabalho no kubernetes, 
dependendo do cluster. Anteriomente conhecido como minion. 
Cada no tem serviços necessários para executar pods e é 
gerenciando pelo componentes do master. Os serviços em nó 
incluem Docker, Kubelet and kube-proxy.

# Estado de um no
