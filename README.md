# Relatório de Importação para Capacetes de Moto, Bicicleta e Automobilismo

# 🚀 Boleto Interno

![Static Badge](https://img.shields.io/badge/status-Active-gren?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/coverage-0-red?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/.NET-4.8-red?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/production-IIODIWINPRD01-gren?style=for-the-badge)

## 📋 Descrição

O objetivo deste projeto é imprimir de forma automática os boletos contidos na tabela F55BOLET
 
## 💻 Pré Requisitos

Para utilizar o projeto é necessário ter instalado em sua máquina:

- [Visual Studio](https://visualstudio.microsoft.com/pt-br/)

> Certifique-se de incluir a carga de trabalho ".NET desktop development" durante a instalação.

- [Oracle Client](https://www.oracle.com/br/database/technologies/instant-client/downloads.html)

## 🛠️ Instalando e Rodando

1. Clone o sistema para seu ambiente com: `git clone https://github.com/starplast/boleto-interno.git`

2. Abrir o Projeto no Visual Studio:

   Abra o Visual Studio.
   No menu, vá para `File -> Open -> Project/Solution`.
   Navegue até a pasta do seu projeto e selecione o arquivo de solução (.sln).

3. Restaurar Pacotes NuGet:

   No Visual Studio, vá para `View -> Solution Explorer`.
   Botão direito no projeto no Solution Explorer e selecione Restore NuGet Packages.

4. Configurar o Projeto Principal:

   Se o seu projeto tiver múltiplos projetos, certifique-se de que o projeto principal (geralmente um projeto com extensão .exe para aplicativos de console ou .csproj para outros tipos) está definido como o projeto de inicialização. Você pode fazer isso clicando com o botão direito no projeto e selecionando Set as StartUp Project.
   Executar o Projeto:

5. Crie uma pasta que irá receber os Logs de erro do programa.

6. Crie uma pasta onde os boletos serão armazenados até serem impressos.

7. Pressione F5 ou vá para `Debug -> Start Debugging` para executar o projeto.

**Atenção** A biblioteca que BoletoNet gera arquivos .tmp no %TEMP% da maquina, assim quando chega no limite de 65.000 e não for limpo a aplicação da um erro de arquivo existente e não imprime os boletos seguintes, para resolver isso no server alocado, existe uma pasta que contém um .bat para remover todos os arquivos diariamente.

## 📫 Contribuindo

Para contribuir, siga estas etapas:

1. Crie uma branch a partir da branch principal: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_branch>`
5. Crie a solicitação de pull.

## 🏁 Realizando Deploy

Para realizar o deploy da aplicação em produção siga os seguintes passos:

1. Confirme se os métodos de deploy estão em "Debug" e "x64" em `Compilação > Gerenciador de Configurações`
   
2. Gere os arquivos de deploy em `Compilação > Compilar Solução`
   
   Os arquivos de deploy serão gerados e armazenados em `BoletoTeste\bin\x64\Debug\app.publish`
   
3. Pegue todos os arquivos e coloque na pasta `C:/Applications/boleto-interno9.2` no servidor de produção.

> Para que o programa rode de acordo, é necessário sempre dexar ele aberto para imprimir os boletos periodicamente.

## 📜 Licença 

Este projeto não está sob nenhuma licença.


