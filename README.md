# postgresql-in-docker
Servidor Postgresql gerenciado pelo PGAdmin4 usando Docker

O projeto contém dois containers docker: O db_postgres, com a última versão do servidor de banco de dados PostgresQL e outro container pgadmin4 com o PGAdmin4.

Pré-Requisitos:
- docker + docker-compose

* Caso não tenha o ambiente Docker, poderá utilizar o https://labs.play-with-docker.com/ para testes!

Quick Start

    Clone ou baixe o repositório
    Acesse o diretório: cd postgresql-in-docker
    Execute o comando: docker-compose up -d
    
 O acesso será através do navegador no endereço http://localhost:8888
 
  usuário: admin@pgadmin.org
  senha: admin

Adicionando um novo servidor no PGAdmin4:

    Host name/address: postgres
    Port 5432
    Username: postgres
    Password: changeme

