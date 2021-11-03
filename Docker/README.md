# Docker

Docker se refere a muitas coisas. Isso inclui: um projeto da comunidade open source; as ferramentas resultantes desse projeto; a empresa Docker Inc., principal apoiadora do projeto; e as ferramentas compatíveis formalmente com a empresa. O fato de que as tecnologias e a empresa têm o mesmo nome pode causar uma certa confusão.

Veja mais sobre:
[Dcoker](https://www.redhat.com/pt-br/topics/containers/what-is-docker)

Link para cursos docker: 

Curso para Iniciantes:
[Preparando desenvolvimento Docker ](https://www.youtube.com/watch?v=c2y_yz9B6_M&list=PLg7nVxv7fa6dxsV1ftKI8FAm4YD6iZuI4)

[Curso de Docker](https://www.youtube.com/watch?v=0xxHiOSJVe8&list=PLf-O3X2-mxDkiUH0r_BadgtELJ_qyrFJ_)

[Containers Fundamentals](https://4linux.com.br/cursos/treinamento/containers-fundamentals/)

[Descomplicando o Docker](https://github.com/badtuxx/DescomplicandoDocker)

Termos Tecnicos Utilizados

Docker volumes: são sistemas de arquivos montados em contêineres Docker para preservar os dados gerados pelo contêiner em execução. Os volumes são armazenados no host, independente do ciclo de vida do contêiner. Isso permite aos usuários fazer backup de dados e compartilhar sistemas de arquivos entre contêineres facilmente.

Docker Daemon – Software que roda na máquina onde o Docker está instalado. Usuário não interage diretamente com o daemon.

Docker Client: CLI ou REST API que aceita comandos do usuário e repassa estes comandos ao Docker daemon.

Docker Engine: Usado para criar imagens e containers.

Docker Registry: Uma coleção de imagens hospedadas e rotuladas que juntas permitem a criação do sistema de arquivos de um container. Um registro pode ser público ou privado.

Docker Hub: Este é um registro usado para hospedar e baixar diversas imagens. Pode ser visto como uma plataforma SAAS de compartilhamento e gerenciamento de imagens.

Dockerfile: Um arquivo texto contendo uma sintax simples para criação de novas imagens.

Docker Compose: Usado para definir aplicações usando diversos containers.

Docker Build: constrói uma imagem a partir de um Dockerfile e de um contexto. O contexto do build é o conjunto de arquivos na localização especificada PATH ou URL. O PATH é o diretório no seu sistema de arquivos local e a URL é a localização do repositório GIT.

Docker Swarm: É uma ferramenta que permite o agrupamento (clustering) de Containers Docker.

Docker Container: Detém tudo que é necessário para uma aplicação ser executada. Cada container é criado a partir de uma imagem.

Docker Imagem: É um template. Uma imagem contém todos os dados e metadados necessários para executar containers a partir de uma imagem.
