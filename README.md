# PacatoBot

Pacatobot é um microbot que usa NodeJs (NightmareJS) para solicitar automaticamente saques da sua conta no PagSeguro.

![Pacatobot](https://gserrano.github.io/assets/imgs/pacatobot.gif)


Para utilizar:

- Faça clone do repositório
- Instale as dependências 
```sh
$ npm install
```

- Ajuste as configurações de acesso da sua conta PagSeguro (deve estar em /src/config.js e o arquivo exemplo está em /src/config.sample)

- Compile
```sh
$ npm run build
```
- Solicitar o saque e automatize esta rotina como for mais conveniente
```sh
$ npm run app
```
ou
```sh
$ node lib/app.js
```