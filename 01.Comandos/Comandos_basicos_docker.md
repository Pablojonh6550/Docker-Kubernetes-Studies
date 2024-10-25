# Criação de container

- `docker pull {nome_do_pacote}` : faz o download do pacote;
- `docker run {nome_do_pacote}` : executa o pacote ao qual foi referenciado;
- `docker ps` ou `docker container ls` : lista todos os containers ativos;
- `docker stop {id ou nome_do_pacote}` : usado para para a execução do container;

# Prefixos

- `-it` : o prefixo permite executar o container em modo interativo;
- `-a` : exibe todos os containers ativos e inativos já executados;
- `-d` : executa o container em modo background (detached);
- `-p` : usada para refletir em qual porta da sua maquina será exposta a porta do container (ex: -p 8080:80);
