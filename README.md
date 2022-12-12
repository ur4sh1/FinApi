# Exercício de Node.js
<h1 align="center">:file_cabinet: FinApi - Api Financeira</h1>

## :memo: Descrição
Exercício de Node.js

## :books: Funcionalidades

[x] Deve ser possível buscar o extrato bancário do cliente<br>
[x] Deve ser possível criar umma conta<br>
[x] Deve ser possível realizar um saque<br>
[x] Deve ser possível realizar um depósito<br>
[x] Deve ser possível buscar o extrato bancário do cliente por data<br>
[x] Deve ser possível atualizar dados da conta do cliente<br>
[x] Deve ser possível obter dados da conta do cliente<br>
[x] Deve ser possível deletar uma conta<br>
[x] Deve ser possível retornar o balance<br>

## :books: Regras de negócio

[x] Não deve ser possível cadastrar uma conta com CPF já existente<br>
[x] Não deve ser possível buscar extrato em uma conta não existente<br>
[x] Não deve ser possível fazer depósito em uma conta não existente<br>
[x] Não deve ser possível fazer saque quando o saldo for insuficiente<br>
[x] Não deve ser possível fazer saque em uma conta não existente<br>
[x] Não deve ser possível excluir uma conta não existente<br>

## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
```
git clone git@github.com:ur4sh1/FinApi.git
```
Instalar o yarn
```
yarn install
```
Executar o projeto
````
yarn dev
```

## :wrench: Histórico de comandos
Instalar o uuid
```
yarn add uuid
```