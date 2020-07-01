# Hello world golang api
Projeto teste Golang + Buffalo com Docker 
[link](https://hub.docker.com/repository/docker/architect42/hello-world-golang-api) da imagem no docker hub.

## Comando para instalar o Buffalo
Acesse a documentação de como instalar [link](https://gobuffalo.io/en/docs/getting-started/installation) ou execute no terminal
```bash
brew install gobuffalo/tap/buffalo
```

## Como executar o projeto
```bash
buffalo dev
```
A aplicação irá rodar na porta 3000 [http://127.0.0.1:3000](http://127.0.0.1:3000) e exibira um JSON com a mensagem "Welcome to Buffalo!"

## Como gerar uma imagem
```bash
docker build -t hello-world-golang-api .
```

## Como criar um container
```bash
docker run -it --name hello-world-golang-api -p 3000:3000  hello-world-golang-api:latest
```
