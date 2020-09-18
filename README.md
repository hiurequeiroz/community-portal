# Community Portal

## Instalação

## Pre-requisites

- Make sure you have NodeJS installed.

## Step-by-setp

- `npm install` to install dependencies 
- `npm run dev` to start to dev.

## Editing you page

- modifique o example.env : `cp example.env .env`
- edite o arquivo .env e modifique as seguintes linhas
 

## Para construir em um computador e jogar para uma rasp

- colocar o tile-server dentro da pasta do portal rode `sh run.sh`
	- erro `ERROR: The image for the service you're trying to recreate has been removed. If you continue, volume data could be lost. Consider backing up your data before continuing.`

- copiar a pasta assets do computador para dentro do tile-server na rasp

- copiar o .env.example para .env e editar

- dentro da pasta tile-server-master rodar `docker build -t tile-server .`

- `npm run build` no projeto do computador e colar a pasta dist para o servidor

- no servidor rodar `docker-compose up -d`	
` 

