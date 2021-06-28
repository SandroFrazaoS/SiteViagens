<h1 align="center">
  <br>
  <br>
  Pagina de reservas de viagens utilizando React com Redux.
</h1>

<h4 align="center">
   Desenvolvido com React + NodeJS + Redux  
</h4>

<h6 align="center">
  bootcamp SujeitoProgramador
</h6>

<br/>

<p align="center">
  <a href="#Pre-Requisitos">Pre-requisitos</a> |
  <a href="#Instalação">Instalação</a> |
  <a href="#Usabilidade">Usabildiade</a>
</p>

# Pre-Requisitos

* [React](https://pt-br.reactjs.org/)
* [Node.JS](https://nodejs.org/)
* [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/get-npm)

# Instalação
```
# Primeiro clone o repositorio do Git para seu computador. Execute o comando; 
git clone https://github.com/SandroFrazaoS/SiteViagens.git

# Acesse a pasta criado atraves do comando; 
cd SiteViagens

# Instale todas as dependencias do projeto, acesse a pasta SiteViagens e execute o comando;
yarn

# Para start do site execute dentro da pasta SiteViagens o comando;
yarn start
```

# Usabilidade

O objetivo desde projeto foi aprender um pouco sobre Redux e Redux Saga. 
Para simular uma API Fake com informações sobre pontos de viagens e passagens disponível por ponto, criei um arquivo JSON chamado server.json  
e utilizei o JSON-Server para gerar meu servidor fake.


JSON-Server é um pacote npm que você pode usar para criar um webservice REST JSON simulando uma API.


O Redux é uma biblioteca feita para gerenciar estados em uma aplicação, ela tira a responsabilidade de um componente ter um estado 
que poderá ser usado por vários outros componentes dentro da sua aplicação e passa isso para um objeto global, 
que pode ser acessado por qualquer componente, a qualquer momento.


Já o redux-saga utilizo como middle entre pagina home e reservas.
Ele é uma biblioteca que foca em fazer os efeitos colaterais em aplicações React/Redux serem mais fáceis e simples de se criar e manter.
Por exemplo chamadas assíncronas para buscar dados em uma API, transformações impuras como acessar o cache do navegador, etc.

No projeto utilizei bibliotecas como
axios, react-router-dom, history, immer, react-icons entre outros.



Tela de principal.

![1][tela1]

Tela de reservas

![2][tela2]


[tela1]: Tela1.png
[tela2]: Tela2.png

