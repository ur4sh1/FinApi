# Exercício de Node.js
<h1 align="center">:file_cabinet: Mobile - FinApi - Api Financeira</h1>

## :memo: Descrição
Exercício de Node.js

## :books: Funcionalidades

-[x] Deve ser possível criar umma conta
-[x] Deve ser possível buscar o extrato bancário do cliente
-[x] Deve ser possível realizar um saque
-[x] Deve ser possível realizar um depósito
-[x] Deve ser possível buscar o extrato bancário do cliente por data
-[x] Deve ser possível atualizar dados da conta do cliente
-[x] Deve ser possível obter dados da conta do cliente
-[x] Deve ser possível deletar uma conta
-[x] Deve ser possivel retornar o balance

## :books: Regras de negócio

-[x] Não deve ser possível cadastrar uma conta com CPF já existente
-[x] Não deve ser possível buscar extrato em uma conta não existente
-[x] Não deve ser possível fazer depósito em uma conta não existente
-[x] Não deve ser possível fazer saque quando o saldo for insuficiente
-[x] Não deve ser possível fazer saque em uma conta não existente
-[x] Não deve ser possível excluir uma conta não existente

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