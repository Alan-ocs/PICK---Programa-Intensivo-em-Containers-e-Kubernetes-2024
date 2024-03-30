No primeiro dia, masterclasse com o Jefersson Badtuxx by LinuxTips, foi explorado os fundamentos do Docker. Aprendemos sobre containers e desmistificamos conceitos como Namespaces, Cgroups e o princípio de Copy-On-Write. Discutimos a importância da interação entre o Kernel Linux e o Docker. Além disso, abordamos tópicos como a criação e gerenciamento de containers, monitoramento de métricas, inspeção de containers, criação e utilização de containers em modo detached, além do uso do comando docker exec. O dia encerrou-se com um exame prático, laboratório e um desafio para consolidar o aprendizado.

Detalhando alguns passos que vi na primeira aula;
- Instalando o Docker com Curl;
-   curl -fsSL https://get.docker.com | bash
- Primeiros Comamdos; Docker Run, Docker Container LS, e LS -a.

- Executando um container em modo daemon.
- Docker container run -it = Interatividade com Terminal
- Ctrl + p & q sai do container sem terminar o container.
- Docker container attach vai conectar ao container em execução.
- Testamos os comandos docker container stop, pause, unpause e start para cuidar do estado do container.
- Finalizando com o comando de remoção, com Docker container rm nomedocontainer.

[![Warp Terminal](run-it.png)](https://app.warp.dev/referral/WZ649Y)

