# DotNet Sample

Este repositório contém um exemplo básico de aplicação utilizando .NET, desenvolvido para demonstrar a criação de um projeto simples sem a necessidade de instalação local de pacotes no Linux.

## O que é .NET?

O **.NET** é um conjunto de bibliotecas utilizadas para resolver diversos problemas no desenvolvimento de software. Normalmente, para utilizá-lo, baixamos pacotes conhecidos como **SDK (Software Development Kit)**.  
Essa "bruxaria" da Microsoft suporta diversas linguagens de programação e pode ser usada em diferentes tipos de projetos, como sistemas corporativos, aplicativos desktop e muito mais.  

### .NET Core  
O **.NET Core** é uma versão open-source do .NET que funciona em múltiplas plataformas, como **Mac**, **Windows** e **Linux**.  

Exemplo de uso: Sistemas desenvolvidos pela INOVA.

---

## O que é ASP.NET?

O **ASP.NET** é uma tecnologia da Microsoft similar ao .NET, mas com foco no desenvolvimento web. Ele é amplamente utilizado para criar aplicações web modernas e escaláveis.

---

## Estrutura do Projeto

Este exemplo contém:
- Um arquivo `Program.cs` com um simples "Hello, World!" escrito em C#.
- Um arquivo `DotNetSample.csproj`, que define as configurações do projeto.

---

## Como Executar

### Use o GitHub Codespaces (Opcional, se disponível)
Se você tiver acesso ao GitHub Codespaces, ele permite criar e testar o projeto .NET sem precisar configurar nada localmente.

Vá até o repositório.
Clique no botão Code e selecione Open with Codespaces.
No Codespaces, digite o seguinte para criar um novo projeto .NET:

bash
    dotnet new console -o DotNetSample
Depois, para rodar o programa:

bash
    cd DotNetSample
    dotnet run

## Commit para repo

    sudo git init
    sudo git add .
    sudo git status
    sudo git commit -m "aplicação utilizando .NET"
    sudo git remote add origin https://github.com/0xxDiego/dotnet-sample.git
    sudo git remote -v
    # Uma vez que estou add commit via browser.
    git config --global --add safe.directory /workspaces/dotnet-sample/DotNetSample
    git pull origin main --rebase

    sudo git push --set-upstream origin main
    
