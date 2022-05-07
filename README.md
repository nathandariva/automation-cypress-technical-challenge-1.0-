# Desafio Tecnico

## Pré Requisito
 - Ter Instalado o node.js na sua máquina
 - Pode realizar o download por aqui: https://nodejs.org/en/download/

## Após ter instalado node

- 1º: clonar o projeto do github
- 2º: executar o comando "npm install" para installar todas as dependências do projeto

## Váriaveis de Ambiente 
 - Nesses testes temos conteúdos sensiveis, então tivemos a necessidade de criar as variaveis de ambiente
 - Na raiz do projeto, criar o arquivo com o nome: cypress.env.json;
 - Neste arquivo deve ser adicionadas o padrão de estrutura apresentada no arquivo "cypress.env.exemple.txt"

 TIMEOUT: deve passar um tempo em milisegungos, exemplo: 10000, para aguardar em até 10s
 EMAIL: deve ter uma conta pré criada, informar seu email aqui
 SENHA: informar a senha correta do respectivo email

 OBS: Fique tranquilo(a), este arquivo estará visivel apenas em sua máquina 

# Como executar os testes

## Modo Open
    - Para acompanhar a execução, no terminal execute o comando:
    npm run test:open
    

## Modo Headless
- Para executar direto no terminal execute o comando:
    npm run test:headless

# Cenários contemplados nessa automação
![login](./readme-img/login.png)

![flow](./readme-img/flow.png)

![allspecs](./readme-img/allspecs.png)
