<h3 align="center">
  Desafio 07: GoFinances Web
</h3>

![](challenge-demo.gif)

## 🚀 Sobre o desafio

Nesse desafio foi desenvolvido a aplicação de gestão de transações, a GoFinances. Nele foi utilizado rotas e envio de arquivos por formulário de modo a colocar em prática o aprendizado do React.js e TypeScript.

Essa é uma aplicação que conecta ao back-end do <a href="https://github.com/andrewdourado/gostack-desafio-typeorm-upload">Desafio 06</a>, exibe as transações criadas e permite a importação de um arquivo CSV para gerar novos registros no banco de dados.

## Instalação

1. Faça o [download](https://github.com/andrewdourado/gostack-desafio-typeorm-upload) e execute o back-end na porta **:`3333`**;

2. Faça o download deste projeto e rode o `yarn` para instalar as dependências e;

3. Rode o `yarn start` para inicar a aplicação.

## Funcionalidades da aplicação

- **`Listagem das transações da API`**: A página `Dashboard` é capaz de exibir uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na API.

- **`Exibição do balance da API`**: A página `Dashboard`, exibe o balance que é retornado do backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importação de arquivos CSV`**: A página Import, permite o envio de um arquivo no formato csv para o backend, que irá fazer a importação das transações para o banco de dados.

## Ferramentas

Nome  | Versão
------------- | -------------
MacOS Catalina  | v10.15.3
Visual Studio Code | v1.44.2
