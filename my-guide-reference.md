# Github
### Criar repositório no github



# Importar repositório
### Importar repositório do github usando git clone <url>
```
$ git clone <Url do Repositório>
```

# Vue Cli
## Instalar vue-cli
```
$ npm install -g vue-cli
```
### Caso já tenha uma versão de Vuejs instalada em sua máquina, deve-se colocar o parâmetro/argumento --force na linha de comando de instalação para forçar a instalação da nova versão.

```
$ npm install -g vue-cli --force
```
# Criar projeto
```
$ vue init <template-name> <project-name>
```
### Para listar os tipos de templates existentes no VueJS, basta executar o seguinte comando

```
$ vue list
```
### Available official templates:

- browserify - A full-featured Browserify + vueify setup with hot-reload, linting & unit testing.
- browserify-simple - A simple Browserify + vueify setup for quick prototyping.
- pwa - PWA template for vue-cli based on the webpack template
- simple - The simplest possible Vue setup in a single HTML file
- webpack - A full-featured Webpack + vue-loader setup with hot reload, linting, testing & css extraction.
- webpack-simple - A simple Webpack + vue-loader setup for quick prototyping.

## Criando o projeto Client
```
$ vue init webpack client
```

Para executar o mesmo, basta acessar a pasta do projeto e executar o comando vue run dev

```
$ cd client
$ npm run dev
```

# Subir projeto para GitHub
```
// Sair da pasta do projeto
$ cd .. 

//Ver status no git
$ git status

//Adicionar todos os arquivos no git
$ git add all

//Subir para o repositórios o projeto e seus respectivos arquivos em questão
$ git commit -m "blablablabla"
```