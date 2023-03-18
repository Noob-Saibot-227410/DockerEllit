# Imagens Docker para estudo e treinamento em TI

Você gosta de Docker? já sabe os comandos? Este repositório contém uma coleção de imagens Docker de diversas tecnologias utilizadas no mercado de TI, disponibilizadas com o objetivo de serem utilizadas para estudo e treinamento.

Cada pasta deste repositório contém uma imagem Docker configurada para a respectiva tecnologia. As instruções de uso de cada imagem podem ser encontradas no arquivo README de cada pasta.

Aproveite bastante!

<h1>Tecnologias disponíveis</h1>

### Tecnologias utilizadas:

<div>
  <img src="https://img.icons8.com/color/48/000000/docker.png">
  <img src="https://img.icons8.com/color/48/000000/python.png">
  <img src="https://img.icons8.com/color/48/000000/nodejs.png">
  <img src="https://img.icons8.com/color/48/000000/react-native.png">
  <img src="https://img.icons8.com/color/48/000000/microsoft-sql-server.png" alt="SQL Server">
  <img src="https://img.icons8.com/color/48/000000/gitlab.png" alt="GitLab">
  <img src="https://img.icons8.com/color/48/000000/ubuntu.png" alt="Ubuntu">
  <img src="https://img.icons8.com/color/48/000000/windows-10.png" alt="Windows">
  <img src="https://img.icons8.com/color/48/000000/mac-os.png" alt="macOS">
  <img src="imgs/postgre.png" alt="PostgreSQL" width="48px">
  <img src="https://img.icons8.com/color/48/000000/terraform.png">
  <img src="https://img.icons8.com/color/48/000000/git.png">
  <img src="https://img.icons8.com/color/48/000000/jenkins.png">
  <img src="https://img.icons8.com/color/48/000000/mysql.png">
  <img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo.png" alt="Java">
  <img src="https://img.icons8.com/color/48/000000/grafana.png" alt="Grafana">
  <img src="https://img.icons8.com/color/48/000000/wordpress.png" alt="WordPress">
  <img src="https://img.icons8.com/color/48/000000/tensorflow.png" alt="TensorFlow">
</div>

<!-- | ![Docker](https://img.icons8.com/color/48/000000/docker.png) Docker | ![Python](https://img.icons8.com/color/48/000000/python.png) Python | ![Node.js](https://img.icons8.com/color/48/000000/nodejs.png) Node.js |
| :-: | :-: | :-: |
| ![React](https://img.icons8.com/color/48/000000/react-native.png) React | ![MySQL](https://img.icons8.com/color/48/000000/mysql.png) MySQL | ![PostgreSQL](https://img.icons8.com/color/48/000000/postgresql.png) PostgreSQL |
| ![Terraform](https://img.icons8.com/color/48/000000/terraform.png) Terraform | ![Git](https://img.icons8.com/color/48/000000/git.png) Git | ![Jenkins](https://img.icons8.com/color/48/000000/jenkins.png) Jenkins | -->

<h1>Principais comandos Docker</h1>
  <img src="https://img.icons8.com/color/48/000000/docker.png">

<h2>Comandos Básicos </h2>
* docker pull: baixa uma imagem do Docker Hub para o seu sistema local.
* docker run: cria um contêiner a partir de uma imagem do Docker.
* docker ps: lista todos os contêineres em execução no momento.
* docker stop: para um contêiner em execução.
* docker rm: remove um contêiner.
* docker rmi: remove uma imagem do Docker do sistema local.
* docker images: lista todas as imagens do Docker no sistema local.

<h2>Comandos de Rede</h2>
* docker network ls: lista todas as redes criadas no sistema local.
* docker network create: cria uma nova rede.
* docker network connect: conecta um contêiner a uma rede.
* docker network disconnect: desconecta um contêiner de uma rede.

<h2>Comandos de Volume</h2>
* docker volume ls: lista todos os volumes criados no sistema local.
* docker volume create: cria um novo volume.
* docker volume rm: remove um volume.

<h2>Comandos de Composição</h2>
* docker-compose up: inicia todos os serviços definidos em um arquivo docker-compose.yml.
* docker-compose down: para todos os serviços definidos em um arquivo docker-compose.yml e remove os contêineres.

<h1>Contribuições</h1>

Este repositório é aberto a contribuições de outras tecnologias e imagens Docker, com o objetivo de ampliar o leque de opções para estudo e treinamento em TI. Se você quiser contribuir, basta clonar este repositório, adicionar as pastas e arquivos necessários e criar um pull request.

Além disso, este repositório está aberto a patrocínios para manter o projeto e expandir ainda mais as tecnologias disponíveis. Se você se interessa em apoiar este projeto, entre em contato conosco e saiba mais.

<h1> Projeto de Brinde aos que patrocinam</h1>
Para ajudar ainda mais no aprendizado, disponibilizamos um projeto de brinde utilizando algumas das tecnologias disponíveis neste repositório. O projeto consiste em uma aplicação web em Node.js que se comunica com um banco de dados MySQL, e está disponível na pasta projeto-de-brinde.