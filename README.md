![example event parameter](https://github.com/github/docs/actions/workflows/main.yml/badge.svg?event=push)

# Example app for CI Hexlet course

Starting boilerplate of [Strapi](https://strapi.io/) application

## Using

```sh
make setup
make start
```

## Run tests

```sh
make test
```

## Run linter

```sh
make lint
```

- uses: actions/checkout@v2
      # run – произвольная bash-команда
      # ls -la выведет содержимое текущего репозитория
      - run: ls -la