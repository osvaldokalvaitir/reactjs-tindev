# ReactJS - Tindev

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/reactjs-tindev/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/reactjs-tindev.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/reactjs-tindev.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/reactjs-tindev.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/reactjs-tindev.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/reactjs-tindev.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/reactjs-tindev.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

Aplicação Tindev usando Create React App, React Router, Axios e Socket.io consumindo os recursos da API do [Node.js - Tindev](https://github.com/osvaldokalvaitir/nodejs-tindev).

## Índice

- [Capturas de Tela](#capturas-de-tela)

  - [Login](#login)

  - [Principal](#principal)

  - [Match](#match)

- [Desenvolvimento](#desenvolvimento)

  - [Configuração do Ambiente](#configuração-do-ambiente)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)
  
- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

## Capturas de Tela

### Login

![Login](/.github/assets/login.png)
Esta é a primeira tela, para entrar o usuário terá que digitar o seu usuário do GitHub e clicar em 'Entrar'.

### Principal

![Principal](/.github/assets/main.png)
É a tela onde estão todos os devs vindos da API, podendo dar like e dislike nos devs existentes.

### Match

![Match](/.github/assets/match.png)
Aparecerá a tela 'It's a match', quando tiver um encontro de likes entre dois devs.

## Desenvolvimento

### Configuração do Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configuração de Ambiente`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md) e siga `Execução de Projeto para Desenvolvimento` ou `Construção e Execução de Projeto para Produção`.

## Utilizados no Projeto

### Bibliotecas

- [Axios](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/axios.md)

- [Create React App](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md)

- [react-router-dom](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/react-router-dom.md)

- [socket.io-client](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/socketio-client.md)

### APIs

- **[Node.js - Tindev](https://github.com/osvaldokalvaitir/nodejs-tindev)**

  - **Rotas**

    - Devs

      - Adiciona novos devs
      - Lista todos os devs que não seja ele mesmo, não esteja nos likes e nos dislikes
      - Likes nos devs
      - Dislikes nos devs