#Procedimento para atualizar versões do Node


## Instruções

1. Baixe o nvm
```bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

2. Recarregar as configurações do seu ambiente
```bash
source ~/.bashrc

3. Listar todas as versões
```bash
nvm list-remote

4. Instalar a versão desejada
```bash
nvm install [version_number]

5. Listar as versões instaladas
```bash
nvm ls

6. Escolher a versão padrão par ao seu sistema
```bash
nvm alias default [version_number]

7. Ativar a versão
```bash
nvm use [version_number]


# Instruções para atualizar versões do Node

Este repositório contém um exemplo de como escolher a versão do Node que deseja usar.

1. Clone este repositório na pasta em que você deseja rodar o projeto:

   ```bash
   git clone https://github.com/seu-usuario/seu-projeto-laravel.git


2. Execute o seguinte comando para iniciar o container:

    ```bash
    docker-compose up -d

O Laravel estará instalado e configurado para se comunicar com a base de dados.
Na porta do phpMyadmin é possível acessar a base de dados.


## Essa composição é voltada para desenvolvimento, em produção é recomendado usar senhas complexas na base de dados
