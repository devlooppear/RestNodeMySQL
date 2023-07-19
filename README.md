# RestNodeMySQL
Projeto de API Rest com NodeJS+MySQL, que é responsável por fornecer endpoints para operações relacionadas a seleções. A API foi construída utilizando o framework Express.js e se conecta a um banco de dados MySQL para persistência dos dados.

## Configuração
Pré-requisitos:
- Node.js: instalado (versão 14 ou superior)
- Banco de dados MySQL: instalado e em execução
- Clonando o repositório
Você pode clonar o repositório deste projeto usando o GitHub Desktop ou qualquer outro cliente Git de sua preferência. Siga as etapas abaixo:

    - Abra o GitHub Desktop em seu computador;

    - Na barra de menu superior, clique em "File" (Arquivo) e selecione "Clone Repository" (Clonar repositório);

    - Na janela "Clone a repository" (Clonar um repositório), escolha a opção "URL" e cole a URL do repositório do projeto;

    - Selecione o diretório local onde você deseja clonar o repositório.
    Clique no botão "Clone" (Clonar) para iniciar o processo de clonagem.
- Instalando as dependências
Após clonar o repositório: Abra um terminal na pasta raiz do projeto e execute o seguinte comando para instalar as dependências necessárias:

```
npm install
```

- Configurando o banco de dados:
(Certifique-se de que o banco de dados MySQL esteja instalado e em execução. Você precisa configurar o banco de dados antes de executar a aplicação). Siga as etapas abaixo:

    - Crie um banco de dados no MySQL para a aplicação;
    - Abra o arquivo ./database/conexao.js e atualize as informações de conexão com o banco de dados, incluindo o nome do banco de dados, o nome de usuário e a senha;
    - Executando a aplicação
    Após instalar as dependências e configurar o banco de dados, você pode iniciar a aplicação;
    - Abra um terminal na pasta raiz do projeto e execute o seguinte comando:

```
npm run dev
```

- A aplicação será iniciada e estará pronta para receber solicitações em http://localhost:3000 por padrão. Certifique-se de que a porta 3000 esteja disponível.

## Endpoints

A API fornece os seguintes endpoints para as operações relacionadas a seleções:

- GET /selecoes
Retorna todas as seleções cadastradas.

- GET /selecoes/:id
Retorna os detalhes de uma seleção específica com base no ID fornecido.

- POST /selecoes
Cria uma nova seleção com base nos dados fornecidos no corpo da solicitação.

- PUT /selecoes/:id
Atualiza os dados de uma seleção específica com base no ID fornecido. Os novos dados devem ser fornecidos no corpo da solicitação.

- DELETE /selecoes/:id
Exclui uma seleção específica com base no ID fornecido.

Certifique-se de incluir os parâmetros corretos nas solicitações, como o ID da seleção.

## Contribuição
Se você quiser contribuir para este projeto, sinta-se à vontade para fazer um fork do repositório e enviar pull requests com suas melhorias.
