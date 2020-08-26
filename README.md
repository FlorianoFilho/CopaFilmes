# Arquivo README

# Solução inicial do Copa Filmes

A API (http://copafilmes.azurewebsites.net/api/filmes) retornará 16 filmes. 

O usuário deverá escolher apenas 8 filmes através de uma listagem para dar
início à competição.

Uma tela exibirá esses filmes, com a possibilidade de o usuário escolher quais entrarão na disputa. 

Na tela terá um contador de quantos filmes já foram escolhidos e um botão dará
início ao campeonato. 

O usuário clicará no botão para enviar os filmes selecionados para o back-end realizar a competição e identificar o vencedor. 

Uma tela exibirá o resultado final da competição, com base nas notas dos filmes selecionados. Caso tenha empate, o vencedor será decidido pela ordem alfabética. 


### Tecnologias utilizadas

Web API (Application Programming Interface) de Back-End com ASP.NET CORE.
SPA (Single-Page Application) de Front-End com React.

### Para executar o projeto na sua máquina

Faça o download do arquivo "CopaFilmesB.zip".
Execute a descompactação em um diretório.
Acesse o diretório do projeto.

Siga os passos para rodar o back-end e front-end. Se necessitar, acesse o arquivo LEIA-ME.pdf para mais detalhes.

### No Visual Studio 
No Visual Studio, acessar o diretório do back-end ".../backende/src" e abrir a solução "CopaFilmesB.sln" 

### No Prompt de comando
Acessar o diretório do back-end ".../src/FilmesCampeonato"

Compilar:  "dotnet build"

Executar: "dotnet watch run"

### No diretório do Frontend
URL: "http://localhost:3000/"

NPM: "npm install && npm start"

YARN: "yarn install && yarn start"


