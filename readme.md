# Documentação da Api

* Escolher um local do computador para criar o projeto
* Abrir o gitBash nesta pasta

Com o gitBash aberto executar o comando para criar a raiz do projeto: (mkir = make diretorio = criar pasta)
```
mkdir NOME_PROJETO 
```
Acessar a pasta:
```
cd NOME_PROJETO
```
Comando para abrir vs.code:
```
code .
```
Criar o arquivo gerenciador de pacotes node:
```
npm init -y
```
Criar arquivo .gitignore (pasta para armazenar arquivos que não serão enviados para o GitHub):
```
touch .gitignore
```
Criar arquivo .env (arquivo para reservar variáveis do projeto):
```
touch .env
```
## Instalar os pacotes do projeto

Instalar pacotes para o projeto
```
npm i express nodemon dotenv
```
* i = install (instalar)
* express = será o servidor da Api
* nodemon = atualiza os arquivos alterados sem parar o servidor
* dotenv: gerenciador de variáveis de ambiente
Criar pasta src:
```
mkdir src
```
Criar arquivo server.js dentro da pasta src:
```
touch src/server.js
```
Adicionar arquivos e pastas no gitignore:
```
node_modules 
.env
```
Iniciar arquivo git:
```
git init
```