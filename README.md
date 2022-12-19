# Repositories API - Ignite NodeJS

<p align="center">
  <img src="https://img.shields.io/static/v1?label=repositories&message=api&color=blueviolet&style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/MrRioja/todos-ignite-correcting-code?color=blueviolet&logo=License&style=for-the-badge"/>
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/MrRioja/todos-ignite-correcting-code?color=blueviolet&logo=JavaScript&logoColor=white&style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/MrRioja/todos-ignite-correcting-code?color=blueviolet&style=for-the-badge">
</p>
<br>

<p align="center">
  <a href="#sobre">Sobre</a> •
  <a href="#repositories-api">Repositories API</a> •
  <a href="#instalação">Instalação</a> •
  <a href="#tecnologias">Tecnologias</a> •
  <a href="#autor">Autor</a>  
</p>

<br>

## Sobre

Projeto proposto no desafio complementar do módulo I da trilha do bootcamp de NodeJS da Rocketseat cujo objetivo foi identificar erros em uma API de template para colocar em pratica os ensinamentos do módulo e praticar o debugging de códigos.

## Repositories API

Essa API é um CRUD de repositórios de projetos e o intuito dela foi servir como base pra pratica de debugging e correção de erros.

O template da API foi entregue no desafio complementar do módulo I do curso com diversos erros e trechos de códigos ausentes para que, após investigação e debugging da API, todos os erros fossem corrigidos e a aplicação estivesse totalmente funcional.

A API é bem simples e possui as rotas abaixo:

<details>
  <summary>GET <code>/repositories</code></summary>
  <br>
  A rota retorna uma lista contendo todos os repositórios cadastrados.
</details>

<details>
  <summary>POST <code>/repositories</code></summary>
  <br>
  A rota recebe <code></code>`title`, <code></code>`url` e <code></code>`techs` pelo corpo da requisição e retorna um objeto com as informações do repositório criado e um status <code></code>`201`.  
</details>

<details>
  <summary>PUT <code>/repositories/:id</code></summary>
  <br>
  A rota recebe <code>title</code>, <code>url</code> e <code>techs</code> pelo corpo da requisição e o <code>id</code> do repositório que deve ser atualizado pelo parâmetro da rota. Altera apenas as informações recebidas pelo corpo da requisição e retorna esse repositório atualizado.
</details>

<details>
  <summary>DELETE <code>/repositories/:id</code></summary>
  <br>
  A rota recebe, pelo parâmetro da rota, o <code>id</code> do repositório que deve ser excluído e retorna um status <code>204</code> após a exclusão.  
</details>

<details>
  <summary>POST <code>/repositories/:id/like</code></summary>
  <br>
  A rota recebe, pelo parâmetro da rota, o <code>id</code> do repositório que deve receber o like e retornar o repositório com a quantidade de likes atualizada.  
</details>

## Instalação

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Além disso é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/todos-ignite-correcting-code.git

# Acesse a pasta do projeto no terminal/cmd
$ cd todos-ignite-correcting-code

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run dev
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn dev

# Execute os testes da aplicação
$ npm run test
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn test

# O servidor inciará na porta 3333 - acesse <http://localhost:3333>
```

## Tecnologias

<img align="left" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="75" />

<img align="left" src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" alt="Express.js" height="75"/>

<br><br><br>

## Autor

<div align="center">
<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/u/55336456?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d" />
<h1>Luiz Rioja</h1>
<strong>Backend Developer</strong>
<br/>
<br/>

<a href="https://linkedin.com/in/luizrioja" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/mrrioja" target="_blank">
<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:lulyrioja@gmail.com?subject=Fala%20Dev" target="_blank">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://api.whatsapp.com/send?phone=5511933572652" target="_blank">
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

<a href="https://join.skype.com/invite/tvBbOq03j5Uu" target="_blank">
<img alt="Skype" src="https://img.shields.io/badge/SKYPE-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white"/>
</a>

<br/>
<br/>
</div>
