# Criação de container

- `docker pull {nome_do_pacote}` : faz o download do pacote;
- `docker run {nome_do_pacote}` : executa o pacote ao qual foi referenciado;
- `docker ps` ou `docker container ls` : lista todos os containers ativos;
- `docker start {id_do_container}` : usado para iniciar um container pausado ou existente;
- `docker stop {id_do_container ou nome_do_pacote}` : usado para para a execução do container;
- `docker logs {id_do_container}` : utilizado para listar todos os logs do container;
- `docker rm {id_do_container}` : utilizado para remover containers;

# Prefixos

- `-it` : o prefixo permite executar o container em modo interativo;
- `-a` : exibe todos os containers ativos e inativos já executados;
- `-d` : executa o container em modo background (detached);
- `-p` : usada para refletir em qual porta da sua maquina será exposta a porta do container (ex: -p 8080:80);
- `--name` : usado para definir o nome do container;
- `-f` : (force) usado para forçar a execução dos comandos;
- `-f` : (atrelado ao docker logs) usado para executar em folow e continuar exibindo as informações do comando;
