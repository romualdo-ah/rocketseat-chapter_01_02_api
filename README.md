# rocketseat-chapter_01_02_api

## Passos para fazer deploy de Json-Server no Heroku
Para ver video clique na seguinte imagem
[![Deploying Json Server on Heroku](https://img.youtube.com/vi/FLnxgSZ0DG4/maxresdefault.jpg)](https://youtu.be/FLnxgSZ0DG4)

# OU
1- Clone este <a href="https://github.com/romualdo-ah/rocketseat-chapter_01_02_api">repositorio</a>. 

      git clone https://github.com/romualdo-ah/rocketseat-chapter_01_02_api.git

2- Na pasta do repositorio clonado, abra o Terminal.

3- Digite yarn install para instalar os pacotes de dependencia do projeto.

4- Modifique a data de server.json com sua data.

5- Tenha certeza de ter na raiz do projeto o arquivo .gitignore com o conteúdo node_modules

6- Pushe o projeto com os seguintes comandos: 
      
    git add .
      
    git commit -m "Subindo o projeto ao gerenciador"
      
    git push
      
7- Instale heroku cli no seu computador. Seguir os passos de instalação nesse <a href="https://devcenter.heroku.com/articles/heroku-cli">Link</a>

8- Na pasta do seu repositorio clonado, escreva o comando:
    
    heroku create <nome-do-seu-projeto>
    heroku login

9- Siga as instruções do Terminal.

10- Clicar no botão login da página aberta.

11- Escrever o comando:

    git push heroku main
    heroku open
    
E logo estara o repositorio Json-Server online.
