# isf-pibd

## Inicialização da base de dados localmente com o docker

- Instale o serviço do docker seguindo o script 

  ```
  install_docker.sh
  ```
- Com os serviços instalados, no diretorio em que se encontra o arquivo `docker-compose.yml` rode o comando

  ```bash
  docker-compose up -d
  ```
- Com isso, será criado um server do postgres com a base de dados ISF-Dev na porta `5555`, e um pgadmin na porta `5050`
- O PgAdmin pode ser acessado em `localhost:5050` com o email `admin@admin.com` e senha padrão `root`
  - Para fazer com que o pgadmin enxergue os arquivos rode o comando `chown -R 5050:5050 SQL`   
- A senha para o server é `root`
  
