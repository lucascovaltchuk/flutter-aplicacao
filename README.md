# Projeto: Aplicação Bancária

## INSTRUÇÕES DE COMO EXECUTAR O PROJETO

### Back-end (API)
1. **Vá para a pasta** chamada `backend/api`.
2. **Execute o comando** abaixo para iniciar o servidor:
   ```bash
   json-server --watch db.json

3. Caso não tenha o json-server instalado, você precisará instalá-lo globalmente no seu computador. Para isso, execute o comando: npm i -g json-server

Front-end (Mobile)
4. Vá para a pasta chamada mobile.
5. Instale a dependência HTTP necessária para fazer requisições no Flutter, executando o seguinte comando: flutter pub add http

Objetivo do Projeto
Muitas aplicações modernas exigem integração com APIs para que suas regras de negócios sejam processadas, validadas e armazenadas em bancos de dados ou outros serviços externos. No caso deste projeto, utilizamos o framework Flutter para realizar requisições HTTP e conectar nossa aplicação móvel a uma API construída com o json-server.

Funcionalidades a serem implementadas:
- Formulário: Criar uma tela contendo um formulário com dois campos – um campo de texto e um campo numérico.
- Lista de Registros: Criar uma tela que exiba uma lista das informações cadastradas pelo formulário. A lista deve permitir ações de criação, edição e exclusão.
Todas as operações de CRUD (criar, ler, atualizar, deletar) serão realizadas via API, sem utilização de armazenamento em memória. Para facilitar a implementação e manter o código organizado, será usada uma classe abstrata que conterá os métodos principais do CRUD, possibilitando a reutilização dos mesmos em outras partes da aplicação.

Tema do Projeto:
O tema central desta aplicação será uma Aplicação Bancária, onde o usuário poderá realizar o cadastro e gerenciamento de dados simulando uma aplicação financeira.

6. Vá para a pasta chamada "back-end/api".
- Dentro dessa pasta, execute o seguinte comando: json-server --watch db.json
7. Abra o terminal (ou linha de comando).
- Para instalar o json-server globalmente no seu computador, execute o seguinte comando: npm i -g json-server
8. Vá para a pasta chamada "mobile".
- Dentro dessa pasta, execute o seguinte comando: flutter pub add http
