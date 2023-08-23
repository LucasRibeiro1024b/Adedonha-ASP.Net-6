# CRUD-Adedonha-ASP.Net-6

## Sobre

O jogo adedonha é bastante popular e divertido. Esse sistema sendo um CRUD completo permite cadastrar categorias e palavras e fazer o relacionamento entre essas duas entidades. O projeto visa ser um repositório para pesquisar palavras por categoria para ir bem no jogo. As funcionalidades envolvem pesquisar todas as palavras e categorias, bem como pesquisar palavras por letra, tendo um design mas voltado para o administrativo. O projeto foi feito utilizando o ASP.Net 6 no padrão MVC.
Utilizei o conceito de code-first com Entity Framework para criar o Banco de Dados.
O Banco de Dados foi gerenciado no SQL Server onde foi possível testar alimentar e gerenciar a base de dados com SQL.
No front-end foi utilizado Páginas Razor com o tamplate Admin Lte 3.2.

## Instalação

No arquivo appsettings.json adicione em ConnectionStrings -> AdedonhaMVC a string de conexão do seu SQLServer.

Utilize o seguinte comando no terminal para executar as Migrations:

```bash
dotnet-ef database update
```

Execute o programa.
