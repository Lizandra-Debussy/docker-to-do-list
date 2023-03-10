# Repositório do projeto Docker To do List

Projeto desenvolvido durante o módulo de Back-End no curso de Desenvolvimento WEB da Trybe .

Docker to-do list possui um aplicativo de tarefas da Trybe chamado Todo_App que permite aos usuários organizar suas tarefas de forma simples, adicionando, marcando e removendo as tarefas criadas. O objetivo deste projeto é containerizar aplicativos, criar uma conexão entre eles e orquestrar seu funcionamento. Para garantir que a aplicação funcione adequadamente, ela foi containerizada, possuindo uma estrutura composta pelo front-end e back-end, cada um com seus respectivos arquivos de configuração e um aplicativo de teste para validar a comunicação entre essas duas frentes.

## Tecnologias e Ferramentas

* ReactJS
* NodeJS
* Docker
* Express
* Eslint

## Requisitos
<details>
  <summary><strong> Requisitos obrigatórios e bônus</strong></summary><br />

1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como 01container e utilizando a imagem alpine na versão 3.12.
2. Inicie o container 01container.
3. Liste os containers filtrando pelo nome 01container.
4. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele.
5. Remova o container 01container.
6. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container.
7. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro.
8. Pare o container 02images que está em andamento.

### Dockerfile
9. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend.
10. Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend.
11. Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests.

### Docker-compose
12. Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar.
</details>
