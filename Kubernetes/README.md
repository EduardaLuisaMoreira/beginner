# Kubernetes

Kubernetes, ou “k8s”, é uma plataforma open source que automatiza as operações dos containers Linux. O Kubernetes elimina grande parte dos processos manuais necessários para implantar e escalar as aplicações em containers. Em outras palavras, se você desejar agrupar em clusters os hosts executados nos containers Linux, o Kubernetes ajudará a gerenciar esses clusters com facilidade e eficiência. Esses clusters podem incluir hosts em nuvem pública, nuvem privada ou nuvem híbrida. Por isso, o Kubernetes é a plataforma ideal para hospedar aplicações nativas em nuvem que exigem escalabilidade rápida.

Veja mais sobre:
[Kubernetes](https://www.redhat.com/pt-br/topics/containers/what-is-kubernetes)

Link para cursos kubernetes: 

Curso para Iniciantes:

[Kubernetes 1](https://www.youtube.com/watch?v=RuNTvYejG90&list=PLXzx948cNtr8XI5JBemHT9OWuYSPNUtXs)

[Kubernetes 2](https://www.youtube.com/watch?v=zz1p3gjyHgc&t=324s)

[Descomplicando o Kubernetes](https://github.com/badtuxx/DescomplicandoKubernetes)

Termos Tecnicos Utilizados

Master: a máquina que controla os nós do Kubernetes. É nela que todas as atribuições de tarefas se originam.

Nó: são máquinas que realizam as tarefas solicitadas e atribuídas. A máquina mestre do Kubernetes controla os nós.

Pod: um grupo de um ou mais containers implantados em um único nó. Todos os containers em um pod compartilham o mesmo endereço IP, IPC, nome do host e outros recursos. Os pods separam a rede e o armazenamento do container subjacente. Isso facilita a movimentação dos containers pelo cluster.

Controlador de replicações: controla quantas cópias idênticas de um pod devem ser executadas em um determinado local do cluster.

Serviço: desacopla as definições de trabalho dos pods. Os proxies de serviço do Kubernetes automaticamente levam as solicitações de serviço para o pod correto, independentemente do local do pod no cluster ou se foi substituído.

Kubelet: um serviço executado nos nós que lê os manifestos do container e garante que os containers definidos foram iniciados e estão em execução.

kubectl: a ferramenta de configuração da linha de comando do Kubernetes.


