# ControleDeContatos
créditos:
https://www.youtube.com/playlist?list=PLJ0IKu7KZpCQKdwRbU7HfXW3raImmghWZ

## Aula 1
__Criação do projeto ASP NET MVC__
* Edição das Views home/index e home/privacy
* Edição da View contato/index 
* Criação da Controller contatoController.cs
* Criação das Views "Criar.cshtml", "Editar.cshtml" e "apagarConfirmacao.cshtml"


## Aula 2
* criação das actions
* modelagem dos Models com EF (Entity Framework)
* migrations
* até agora, foi feito apenas o "esqueleto" de tudo

**instalados os pacotes NuGet:**
- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.Design
- Microsoft.EntityFrameworkCore.Tools
- Microsoft.EntityFrameworkCore.SqlServer

*** OBS: é necessário ter o MSSQL Server instalado na máquina ***

**Foram adicionados:**
- Data/BancoContext.cs
- "ConnectionStrings : {}" em appsettings.json
- no package manager console foi executada a linha: "Add-Migration CriandoTabelaContatos -Context BancoContext" criou a Migration
- depois: "UpdateDatabase -Context BancoContext" (criou o banco no sqlserver)
