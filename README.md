# Docker Todo List 

## Sobre
 Docker Todo List é um projeto com o objetivo de treinar docker: a partir de uma aplicação fullStack - aplicativo de tarefas pronta, foi feito a conteinerização, criação de uma conexão entre elas, e o orquestramento do funcionamento.

## Arquivos
Os seguintes arquivos foram desenvolvidos por mim:
- pasta docker/docker-commands
- todos os arquivos command01.dc até command10.dc
  A Trybe forneceu a configuração inicial do projeto no arquivo `package.json`.

## Tecnologias
As seguintes tecnologias foram aplicadas por mim neste projeto:
- Docker;

## Desafios

## Desafio 1 - command01.dc
    Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12
    
## Desafio 2 - command02.dc
    Inicie o container 01container

## Desafio 3 - command03.dc
    Liste os containers filtrando pelo nome 01container

## Desafio 4 - command04.dc
   Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele

## Desafio 5 - command05.dc
   Remova o container 01container
   
## Desafio 6 - command06.dc
   Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container.
   
## Desafio 7 - command07.dc
   Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro
   
## Desafio 8 - command08.dc
   Pare o container 02images que está em andamento.

## Desafio 9 - command09.dc
   Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend.

## Desafio 10 - command10.dc
  Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend
   
