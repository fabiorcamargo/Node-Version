# Instruções para Iniciar um Container Laravel

Este repositório contém um exemplo de como iniciar um container do Laravel usando o Docker Compose.

## Pré-requisitos

- Docker: Certifique-se de que o Docker esteja instalado em sua máquina. Você pode baixá-lo [aqui](https://www.docker.com/get-started).
- Docker Compose: Verifique se você também tem o Docker Compose instalado. Ele geralmente é instalado junto com o Docker, mas você pode encontrá-lo [aqui](https://docs.docker.com/compose/install/).

## Configuração

Antes de rodar, verifique se as portas não estão sendo utilizadas, se necessário troque o número das portas:
ports:
      - '8010:8000'

1. Clone este repositório na pasta em que você deseja rodar o projeto:

   ```bash
   git clone https://github.com/seu-usuario/seu-projeto-laravel.git


2. Execute o seguinte comando para iniciar o container:

    ```bash
    docker-compose up -d

O Laravel estará instalado e configurado para se comunicar com a base de dados.
Na porta do phpMyadmin é possível acessar a base de dados.


## Essa composição é voltada para desenvolvimento, em produção é recomendado usar senhas complexas na base de dados