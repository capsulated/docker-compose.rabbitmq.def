# Docker-compose for RabbitMQ with definitions.json in rabbitmq.config

## Install

```
git clone git@github.com:sylogex/rabbitmq-compose.git
cd rabbitmq-compose-definitions
docker-compose up
```

## Use
Open [http://localhost:15672/](http://localhost:15672/)

```
open http://localhost:15672/
```
The default username and password are guest/guest

```
username: guest
password: guest
```

Edit definitions.json for exchanges, queues, bindigs as you want!