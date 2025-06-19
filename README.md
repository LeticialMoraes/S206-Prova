# Resolução Da Prova de S206

## Postman

### 📋 Descrição
Este projeto contém 4 cenários de testes automatizados realizados com o Postman e executados com o Newman, utilizando as APIs públicas **FakeStoreAPI** e **ReqRes API**. Os testes abrangem métodos `GET`, `POST`, `DELETE` e um cenário **negativo** com `POST` inválido.
O relatório dos testes foi gerado com o `newman-reporter-htmlextra` em formato HTML interativo.

### 🚀 Como Executar o Projeto

### 1. Instale o Newman e o gerador de relatórios HTML extra
Se ainda não estiverem instalados, execute o seguinte comando no terminal:

```bash```
* npm i newman
* npm i newman-reporter-htmlextra

### Execute a collection de testes
Execute o comando para que seja gerado o relatorio:
*  newman run Prova.postman_collection.json -r htmlextra

---

## Cypress

### 📋 Descrição
Este projeto contém testes automatizados com Cypress para o site [https://demoqa.com](https://demoqa.com), cobrindo cenários positivos e negativos de formulários, tabelas e checkboxes.

### 🧪 Testes Implementados

- ✅ Formulário com preenchimento completo
- ❌ Formulário com e-mail inválido (teste negativo)
- ✅ Cadastro de novo usuário na tabela dinâmica
- ✅ Seleção de múltiplos checkboxes

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash```
git clone https://github.com/LeticialMoraes/S206-Prova.git
cd S206-Prova

### 2. Instale as dependências

```bash```
* npm install cypress --save-dev

## ▶️ Executando os testes

### Modo interativo (com interface gráfica):

```bash```
npx cypress open
Selecione o navegador desejado e execute o arquivo `prova1.cy.js`.

### Modo headless (terminal):

```bash```
npx cypress run

## 📊 Geração de Relatório com Mochawesome
### 1. Instale o Mochawesome:

```bash```
* npm i cypress-mochawesome-reporter

### 2. Execute os testes com o reporter:

```bash```
npx cypress run --reporter mochawesome



