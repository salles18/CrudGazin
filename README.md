# Projeto CRUD com Node.js, React & MySQL

Este é um projeto de exemplo que demonstra a implementação de um aplicativo CRUD (Create, Read, Update, Delete) usando Node.js para o backend, React para o frontend e MySQL como banco de dados.

## Pré-requisitos

Antes de começar, certifique-se de ter os seguintes pré-requisitos instalados em sua máquina:

- Node.js e npm (Node Package Manager): [Download e instalação do Node.js](https://nodejs.org/)
- MySQL Server: [Download e instalação do MySQL Server](https://dev.mysql.com/downloads/mysql/)

## Instalação

1. Clone este repositório para sua máquina local:

    ```bash
    git clone https://github.com/seu-usuario/Crudgazin.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd crudgazin
    ```

### Configuração do Backend (Node.js)

3. Navegue até o diretório do backend:

    ```bash
    cd api
    ```

4. Instale as dependências do backend:

    ```bash
    npm install
    ```

5. Configure as variáveis de ambiente editando no arquivo `db.js` no diretório `api` e adicione as informações do banco de dados:

    ```plaintext
    DB_HOST=localhost
    DB_USER=root
    DB_PASSWORD=070707
    DB_DATABASE=crud
    ```

6. Execute o servidor backend:

    ```bash
    npm start
    ```

    O servidor estará sendo executado em `http://localhost:3001`.

### Configuração do Frontend (React)

7. Navegue até o diretório do frontend:

    ```bash
    cd frontend
    ```

8. Instale as dependências do frontend:

    ```bash
    npm install
    ```

9. Execute o aplicativo frontend:

    ```bash
    npm start
    ```

    O aplicativo estará sendo executado em `http://localhost:3000`.

## Uso

Após seguir as etapas de instalação, você pode acessar o aplicativo CRUD em seu navegador. O aplicativo permite criar, visualizar, atualizar e excluir Usuarios do banco de dados MySQL.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou relatar problemas.
