# front-end-challenge
[Demo](http://amaro.herokuapp.com/)
## Demo
http://amaro.herokuapp.com/

## Features
- Lista de produtos
- Carrinho (Adicionar, remover, alterar quantidade)

## Estruturas de pasta
```sh
.
├── components // Components
├── data //Products
├── src //source
├── public //webpack build
├── node_modules //dependencias
├── package.json
├── server.js //Nessesário para o deploy no heroku
└── webpack.config.js
```

## Ferramentas e frameworks
- ES6
- SCSS
- ReactJS
- Webpack
- Gulp
- Bootstrap
- Material-UI

## Compilando as folhas de estilos SASS
Primeiro instale o gulp-CLI
```sh
> npm install gulp-cli -g
```
Instale as depências nessesárias com:
```sh
> gulp install
```
Compile com:
```sh
> gulp sass:watch
```

## Rodando no localhost
Primeiro é nescessário instalar as dependências

```sh
> npm install
```

Para rodar o projeto basta:

```sh
> npm start
```

Abra `http://localhost:8080`;

Contato: `joaoantoniomaruti@gmail.com`