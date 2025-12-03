App Livros Pessoais (Mobile)
===========================

Aplicativo desenvolvido em React Native (Expo) para gerenciamento de leitura pessoal. O app consome a API REST da Livraria para persistir os dados.

Funcionalidades
------------------

-   Listagem de livros cadastrados.

-   Formulário para adicionar novos livros.

-   Funcionalidade de **Edição** (alterar status, corrigir erros).

-   Funcionalidade de **Exclusão**.

-   Interface com tema escuro (Dark Mode).

Tecnologias Utilizadas
-------------------------

-   **React Native**

-   **Expo Go**

-   **Axios**

Configuração Importante (IP)
-------------------------------

Para que o aplicativo no celular ou emulador consiga acessar o seu computador, você precisa configurar o IP.

1.  Abra o arquivo `App.js`.

2.  Localize a linha com `const API_URL`.

3.  Substitua pelo endereço IPv4 da sua máquina.

```
// Exemplo no App.js
const API_URL = '[http://192.168.1.15:3000/livros](http://192.168.1.15:3000/livros)';

```

> **Nota**: Não use `localhost` se estiver testando no celular físico, pois o celular não entenderá que "localhost" é o seu computador.

Como Rodar o App
--------------------

1.  **Clone o repositório**:

    ```
    git clone <seu-link-do-git>
    cd mobile-livros

    ```

2.  **Instale as dependências**:

    ```
    npm install

    ```

3.  **Inicie o Expo**:

    ```
    npx expo start

    ```

4.  **Execute**:

    -   **Celular Físico**: Baixe o app *Expo Go* e escaneie o QR Code.

    -   **Emulador**: Pressione `a` (para Android) ou `i` (para iOS) no terminal.

*Desenvolvido para fins acadêmicos.*
