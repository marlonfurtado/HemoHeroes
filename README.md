# HEMOHEROES

Travis: [![Build Status](https://travis-ci.org/marlonfurtado/HemoHeroes.svg?branch=master)](https://travis-ci.org/marlonfurtado/HemoHeroes)

HemoHeroes é uma aplicação para conectar Bancos de Sangue aos doadores em potencial.

## Ambientes
* Staging: http://hemoheroestw-staging.herokuapp.com
* Produção: http://hemoheroes.herokuapp.com/

## Histórias
https://github.com/aceleradora-TW/HemoHeroes/issues

## Style Guides | Best Practices | Tools
[github.com/aceleradora-TW/HemoHeroes/wiki/Best-Practices](https://github.com/aceleradora-TW/HemoHeroes/wiki/Style-Guides-%7C-Guides-%7C-Best-Practices)

## Rodar a aplicação

Para rodar a aplicação localmente você precisa executar os seguintes passos:

1. `$ git clone https://github.com/aceleradora-TW/HemoHeroes.git`
2. `$ cd HemoHeroes`
3. `$ sudo chmod +rwx bin/docker.sh` Se o arquivo docker.sh não for executável.
4. `$ sudo ./bin/docker.sh` para instalar o docker e docker-compose se ainda não os tiver.
5. Deslogar e logar
6. `$ sudo service docker start`
7. `$ docker-compose build web`
8. `$ docker-compose up web`

Agora acesse: localhost:3000

#### Dicas
1. Para executar comando com Docker, execute assim: `$ docker-compose run web COMANDO QUE QUER EXECUTAR`.
Exemplo: `$ docker-compose run web rake db:migrate`

2. Para executar o terminal dentro do Docker, execute: `$ docker-compose run web bash`.
