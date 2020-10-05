# Ruby on Rails 6 Development Environment

## Quickstart

https://docs.docker.com/compose/rails/

## Ruby version

- ruby:2.7.2

Update `Dockerfile`.

# up

```
docker-compose up -d
docker-compose run --rm web rails db:create
```

Open `http://localhost:3000` in your browser.

## Rails version

- 'rails', '~> 6.0', '>= 6.0.3.3'

Update `Gemfile`.

# build

```
docker-compose up -d --build
```
