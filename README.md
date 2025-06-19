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
