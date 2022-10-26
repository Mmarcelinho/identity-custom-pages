# IdentityCustomPages

![id1](https://user-images.githubusercontent.com/97993630/191821033-a15a1d72-c5e7-41b2-a5d0-9c3f571b79da.png)

## Requisitos:
```ASP NET CORE 3.1```
```VS CODE```


**Crie um projeto no modelo mvc com autenticação individual e net core app 3.1:**


```<dotnet new mvc -f netcoreapp3.1 --auth individual>```


**Adicione as referências de pacote NuGet necessárias ao arquivo de projeto ( .csproj):**


```<dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design --version 3.1.5>```

```<dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 3.1.5>```


**Execute o Identity scaffolder com as opções desejadas, utilizando --files para gerar arquivos específicos e passando o nome do contexto do banco de dados:**

```<dotnet aspnet-codegenerator identity -dc ProjectName.Data.ApplicationDbContext --files "Account.Register;Account.Login">```

**Após gerar, customize a page**


**Rodando o projeto:**


```<dotnet run>```

**O projeto será executado em http://localhost:5000/**
