# docker-laravel-containers
Add your Laravel project to a folder named app so your project looks like so:

Your Project
  - ./docker/
  - ./app/
  - docker-compose.yml
  - Readme.md

Run docker-compose up -d to start the contaniners

## Useful commands as aliases
```
alias ddcup=docker-compose up -d
alias ddcompi=docker-compose run --rm composer install
alias ddnpm=docker-compose run --rm npm
alias ddartm=docker-compose run --rm artisan migrate
alias ddgulp=docker-compose run --rm gulp
alias ddbash=docker-compose run --rm app bash
```


