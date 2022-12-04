# Hello, Docker!
Estudos iniciais a fim de entender mais sobre Docker.

## Comandos úteis
* docker ps: lista os containers ativos
* docker ps -a: lista todos os containers
* docker run -p local_port:container_port <nome_servico>: cria e executa um container baixando imagem no Docker Hub / -p faz a referência de portas
* docker exec -it <nome_container> bash: habilita a execução de comandos no terminal dentro do container / -it modo interativo
* docker stop <nome_container>: encerra a execução de um container
* docker start <nome_container> executa um container que já está criado
* docker rm <container_name> -f: exclui um container
