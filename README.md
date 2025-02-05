# 🚀 Boleto Interno


## 📋 Descrição

O objetivo deste repositório é armazenar arquivos excel(.xlsx), dos Importadores de Capacete de Moto, Bicicleta, Automobilismo e Extras.
 
## 💻 Pré Requisitos

Este repositório será usado no site: 
-> [Google Colab](https://colab.research.google.com/)

## 🛠️ Instalando e Rodando

1. Abrir o Google Colab e escolher qual Notebook será utilizado:

   Importação de Capacetes de Moto
   
   Importação de Capacetes de Bicicleta
   
   Importação de Capacetes de Automobilismo

3. Abrir o Notebook e se conectar na rede para execução:

   Clicar no botão 'Conectar' na parte direita do Colab

4. Abrir a opção 'Arquivos', um ícone na forma de uma pasta, na parte esquerda:

   Dentro de 'Arquivos', clicar na opção 'Fazer upload para o armazenamento da sessão', um ícone na forma de um arquivo em upload

5. Upload de arquivos do computador do usuário:

   Do computador do usuário, abrirá os arquivos e neste deverá ser escolhida a base bruta das importações, arquivo Excel, 'Relatório de Importação' ou nome que corresponda a essa base

6. O Notebook estará divido em:

   Bibliotecas: compõe todas as bibliotecas utilizadas para execução do programa
   Importação: compõe a chamda dos importadores
   Código: a execução principal do código

7. No Notebook, na divisão 'Importação':

   A linha de código indicada terá uma variável, está armazena o link que está no Github, o link terá o seguinte padrão: [Link](https://raw.githubusercontent.com/FredericoCS1/Importacoes/main/Importadores/importadoresMoto.xlsx)
   Explicação:
   -> O link é uma URL, contendo 'raw.githubusercontent.com' que é padrão para que possa ser usado dentro do Colab
   -> /FredericoCS1 é o nome do responsável pela criação do repositório, no qual o link está armazenado
   -> /Importacoes/main/Importadores/importadoresMoto.xlsx é o caminho do link
   -> Importacoes é o nome do repositório, que posseui um main branch, que armazena a pasta Importadores, contendo o arquivo importadoresMoto.xlsx, que é um arquivo Excel que foi baixado.

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


