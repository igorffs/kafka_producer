# KafkaProducer

The goal of this pet-project is to build an example of how to produce messages to kafka using [`gen_stage`](https://github.com/elixir-lang/gen_stage) with [`brod`](https://github.com/klarna/brod).


## Setup

This application is using [`asdf`](https://github.com/asdf-vm/asdf) to define Elixir's version and [`docker-compose`](https://docs.docker.com/compose/) to make Kafka's local setup easier.

* Run `asdf install` to install Elixir
* Run `mix do deps.get, compile`
* Run `docker-compose up --abort-on-container-exit --remove-orphans` to start kafka locally






