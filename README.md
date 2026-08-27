# 🎮 Jogo da Forca no Terminal (CLI Hangman)

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

Um projeto simples, clássico e interativo do **Jogo da Forca** desenvolvido inteiramente em **Node.js**, executado diretamente pelo terminal (CLI) com foco no aprendizado e aprimoramento de lógica de programação.

---

## 🎯 Objetivo do Projeto

Este projeto foi criado com o intuito de praticar lógicas de programação com JavaScript, manipulação de estruturas de controle (como laços `while` e condicionais), manipulação de arrays e assincronidade utilizando a API nativa do Node.js (`readline/promises`).

---

## ✨ Funcionalidades

* **Seleção Aleatória:** O jogo sorteia uma palavra diferente a cada execução a partir de uma lista pré-definida de conceitos voltados ao ecossistema backend.
* **Interface Interativa:** Leitura e processamento de entradas do usuário em tempo real direto no terminal utilizando `readline/promises`.
* **Sistema de Vidas:** O jogador possui um total de **6 chances (vidas)** de erro antes que o jogo termine.
* **Feedback Visual:** Exibição dinâmica da palavra atual com as letras descobertas (`_ _ _ _`) e mensagens de status a cada tentativa.

---

## 🚀 Tecnologias Utilizadas

* **[Node.js](https://nodejs.org/)** — Ambiente de execução JavaScript server-side.
* **JavaScript (ES6+)** — Linguagem de programação da lógica principal.
* **Módulo `readline/promises`** — Módulo nativo do Node.js para gerenciamento de input/output via terminal de forma assíncrona com `async/await`.

---

## ⚙️ Como Executar o Projeto

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em sua máquina.

### 1. Criar o arquivo
Crie um arquivo em seu computador chamado `index.js` e cole o código-fonte do jogo.

### 2. Executar a aplicação
Abra o terminal na pasta onde o arquivo está salvo e execute o comando:

```bash
node index.js