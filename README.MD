##Procedimento para atualizar versões do Node

``diff
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

source ~/.bashrc

nvm list-remote

nvm install [version_number]

nvm ls

nvm alias default [version_number]

nvm use [version_number]
