# TesteGitHut

Exercicio de fixação GitHub

Criando um novo repositório com um arquivo .txt.

Criando uma nova branch e subindo o arquivo .txt atualizado.



Iniciando um repositório local:

Ao abrir o terminal, podemos dar o comando para iniciar o repositório local:
> git init

Uma vez com o repositório iniciado, podemos comitar o nosso projeto e deixá-lo pronto subi-lo para o GitHub. O primeiro passo é adicioná-lo:
> git add nome_do_arquivo

Podemos também adicionar todos os arquivos de uma vez usando o ponto final:
> git add .

Então, precisamos comitar esses arquivos:
> git commit -m "Descrição do commit"

É importante sempre descrever os seus commits, pois quando for necessário buscar alguma alteração podemos facilmente identificar através da mensagem. 


Conectando o local com o remoto:

Quando já criamos o nosso repositório local e fizemos o primeiro commit, vamos copiar os comandos da segunda parte das instruções. Primeiro temos que adicionar o caminho remoto para o nosso repositório:
> git remote add origin caminho_do_github

Precisamos falar qual branch o projeto ficará:
> git branch -M main

E subir o projeto para o repositório remoto:
> git push -u origin main

Depois de fazer esse comando pela primeira vez no projeto, os próximos commits pode ser levado para o repositório remoto com apenas um git push


Se o repositório já existe é mais fácil usar o git clone:
> git clone git@github.com:usuario/repositoriogithub.git

Pronto. Faça as alterações necessárias. Para subir os arquivos você precisa fazer o seguinte:

> git add .
> git commit -m 'Sua mensagem de commit'
> git push -u origin master
