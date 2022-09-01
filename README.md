# Projeto Docker Commands

Este projeto foi desenvolvido no modulo de BackEnd do curso da Trybe, e tinha como objetivo exercitar o uso de Docker e Docker Compose, trabalhando com alguns comandos básicos e com a conteinerização de uma aplicação full-stack. O código da aplicação todo-app foi completamente produzido pela Trybe, sendo de minha autoria os comandos docker e os arquivos Dockerfile e docker-compose.yml.

## Técnologias usadas
<p align="left">
  <a href="https://www.docker.com/">
    <img align="center" alt="Docker" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg">
  </a>
</p>

## Para iniciar e executar o docker-compose
```bash
cd ~/project-docker-compose/docker
docker-compose up -d
``` 

## Para iniciar e executar os containers individuais
```bash
docker build -t <nome> ~/project-docker-compose/docker/todo-app/<pasta>
docker exec -it <nome>
``` 
