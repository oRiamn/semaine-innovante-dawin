# innovation-week-dawin
Repository for the innovation week of LP DAWIN

# Requirements

- Nodejs / npm

# Setup

## Clone
- `git clone https://github.com/sylvainmetayer/semaine-innovante-dawin.git`

OU

- `git clone git@github.com:sylvainmetayer/semaine-innovante-dawin.git`

## Install dependencies

- `npm install`

- `npm install -g gulp-cli`

## Setup config file

- cp app/config.json/sample app/config.json

# How to run develop mode ?

- On two separate terminal, run the following commands :
    - `gulp serve`
    - `php -S localhost:8080 -t app/api/`

# Gulp tasks

- `gulp deploy` : Will deploy to the github page repo

- `gulp build` : Will build a production version, located in dist/ folder

- `gulp serve:dist` : Will run a external production version accessible on port 9000

- `gulp serve` : Run on port 9000 the app (dev mode). Auto reload on change.

- `gulp clean` : Clean all temporary files.
