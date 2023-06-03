# Cadastro de Contatos

Este é um projeto de cadastro de contatos desenvolvido em C# utilizando o framework ASP.NET Core. O objetivo deste projeto é permitir que os usuários possam cadastrar, visualizar, atualizar e excluir contatos em um banco de dados SQL Server.

## Linguagens de programação utilizadas

- C#
- SQL

## Pré-requisitos

- Visual Studio ou Visual Studio Code
- .NET Core SDK
- SQL Server

## Instalação

1. Clone ou faça o download do repositório [Cadastro de Contatos](https://github.com/Wgleyberton/Cadastro-de-Contatos).

2. Abra o projeto em um editor de código ou no Visual Studio.

3. Execute o migration do Entity Framework Core para criar o banco de dados no SQL Server. Abra um terminal e navegue até a pasta raiz do projeto e execute o seguinte comando:

```
dotnet ef database update
```

Este comando irá aplicar as migrações pendentes e criar o banco de dados no SQL Server.

4. Abra o arquivo `appsettings.json` localizado na pasta `CadastroDeContatos` e atualize a string de conexão ao banco de dados SQL Server de acordo com as configurações do seu ambiente.

```json
"ConnectionStrings": {
    "DefaultConnection": "Data Source=SERVIDOR;Initial Catalog=NOME_DO_BANCO_DE_DADOS;Integrated Security=True;"
}
```

Substitua `SERVIDOR` pelo nome do servidor do SQL Server e `NOME_DO_BANCO_DE_DADOS` pelo nome desejado para o banco de dados.

## Utilização

Após configurar o banco de dados e a string de conexão, você pode executar o projeto e acessar a interface de cadastro de contatos através do seu navegador. O projeto possui as seguintes funcionalidades:

- Cadastrar um novo contato.
- Visualizar todos os contatos cadastrados.
- Atualizar as informações de um contato.
- Excluir um contato.

## Contribuição

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma [issue](https://github.com/Wgleyberton/Cadastro-de-Contatos/issues) ou enviar um pull request.
