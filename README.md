Invictus - API :postman:

Projeto de automação de API com o Postman.
Projeto voluntário supervisionado pela Qa.Coders para Testes de API executado pela equipe Invictus

Instalação

npm install -g newman npm install -g newman-reporter-htmlextra

Clone o projeto:

  git clone https://github.com/alineibaldo/invictus-academyt14-api-postman.git
 
Para rodar os testes, rode os seguintes comandos:

Newman

  newman run 1-Login_collection.json -e main_environment.json -g postman_globals.json
 
  newman run invictus.postman_collection.json -e Enviroment ERP.environment.json -g workspace.postman_globals.json 
 
 
Equipe


 