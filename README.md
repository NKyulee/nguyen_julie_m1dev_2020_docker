# Nguyen_Julie_M1Dev_2020_docker

<img src="https://cdn.iconscout.com/icon/free/png-512/docker-226091.png"  width="120" height="120">

<img src="https://codingthesmartway.com/wp-content/uploads/2019/01/mern_logo.png" width="20%">

<img src="https://static.wixstatic.com/media/689356_6002e82c98d54c64948c2e323896032c~mv2.png/v1/fill/w_208,h_208,al_c,q_85,usm_0.66_1.00_0.01/MyDigitalSchool.webp"  width="120" height="120">

## Introduction

Dans le cadre de ma formation en Master en tant que Developpeur full stack, je suis un module sur l'utilisation de Docker.
Ce repository contient le rendu de mon projet sur Docker.

Rendu le 05/10/2020.

Le but de ce projet est d’intégrer le déploiement d’une API Rest avec Docker afin de pouvoir l’intégrer
dans un système d’intégration continue et de développement continue.

## Technologies utilisées

- Back-end : NodeJs - Express
- Front-end : ReactJs
- Database NoSQL : MongoDB
- Deploiement : Docker

## Docker Images

Possibilité de récuperer ces images via la commande : 

```bash
docker image goulax/nguyen_julie_m1dev_2020_docker_frontend
docker image goulax/nguyen_julie_m1dev_2020_docker_backend
```


[DockerHub Image Frontend](https://hub.docker.com/repository/docker/goulax/nguyen_julie_m1dev_2020_docker_frontend)

[DockerHub Image Backend](https://hub.docker.com/repository/docker/goulax/nguyen_julie_m1dev_2020_docker_backend)

## Utilisation de l'API REST

### Installation

#### Installation de Docker

1. Installer Docker-cli ou Docker Desktop sur votre machine.

2. Connectez vous avec vos identifiant Docker sur Docker-CLI ou sur Docker Desktop.

3. Vous pouvez maintenant utiliser les commandes Docker !

#### Installation de l'API Rest avec Docker

1. Cloner le repository sur votre machine

```bash
git clone https://gitlab.com/Kyulee/nguyen_julie_m1dev_2020_docker.git
```

2. Cette commande va permettre d'initialiser et démarrer les 3 containers :
- 1er Container : Frontend
- 2ème Container : Backend
- 3ème Container : MongoDB 

```bash
docker-compose up --build
```

3. Rendez vous dans votre browser/navigateur internet et taper l'url suivant : 
http://localhost:3000

4. Vous pouvez désormais vous enregister, vous connecter et poster ce que vous voulez !

