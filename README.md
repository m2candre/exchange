**OneExchange**
===================

![ruby](https://img.shields.io/badge/Ruby-2.4.1-red.svg)
![rails](https://img.shields.io/badge/Rails-5.1.0-red.svg)
![rails](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg)

## Sobre o projeto

Sistema incrivelmente simples para conversão de moedas.

## [Clique e veja online](https://m2candre-exchange.herokuapp.com/)

![exchange](https://cloud.githubusercontent.com/assets/2129551/25876052/44965c96-34f1-11e7-9ed9-4ca441bc1742.png)


# Stack
```
  * Application
```

# Dependencies
```
  * Fixer.io to consult currency rates
```

# Getting Started
```
  * docker-compose build
  * docker-compose run --rm website rake db:create db:migrate
  * docker-compose up
```

# Test
```
  * docker-compose run --rm website rspec
```
