#Procedimento para atualizar versões do Node


## Instruções
1º Baixe o nvm
```bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

2º Recarregar as configurações do seu ambiente
```bash
source ~/.bashrc

3º Listar todas as versões
```bash
nvm list-remote

4º Instalar a versão desejada
```bash
nvm install [version_number]

5º Listar as versões instaladas
```bash
nvm ls

6º Escolher a versão padrão par ao seu sistema
```bash
nvm alias default [version_number]

7º Ativar a versão
```bash
nvm use [version_number]
