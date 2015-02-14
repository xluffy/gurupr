# GURU-PR [![Build Status](https://travis-ci.org/guru-pr/gurupr.svg?branch=master)](https://travis-ci.org/guru-pr/gurupr) [![Code Climate](https://codeclimate.com/github/guru-pr/gurupr/badges/gpa.svg)](https://codeclimate.com/github/guru-pr/gurupr) [![Test Coverage](https://codeclimate.com/github/guru-pr/gurupr/badges/coverage.svg)](https://codeclimate.com/github/guru-pr/gurupr)

Site do Grupo de Usuários Ruby do Paraná!

Utilizamos:
- Github para autenticação
- Heroku
- PostgreSQL

De resto, vamos desenvolvendo aos poucos!

## Instalação

```bash
cp .env.example .env # copie e configure as chaves
bundle install
rake db:create db:migrate
rails server
```

## TODO

- ~~Melhorar~~ Fazer o layout
- Configurar timezone para `Brasilia`
- Mini administração para eventos
- Melhorar specs

## Feito

- ~~Adicionar eventos~~
- ~~Travis!~~
- ~~Codeclimate!~~
