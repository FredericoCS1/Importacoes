# 🚀 Boleto Interno


## 📋 Descrição

O objetivo deste repositório é armazenar arquivos excel(.xlsx), dos Importadores de Capacete de Moto, Bicicleta, Automobilismo e Extras.
 
## 💻 Pré Requisitos

Este repositório será usado no site: [Google Colab](https://colab.research.google.com/)

## 🛠️ Instalando e Rodando

Relatório explicado a execução do programa [Passo a Passo - Google Colaboratory]

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


