### Dev environment wordpress blog ###

#### Requirements ####

* Docker version 17.06.0-ce+
* docker-compose version 1.15.0+

#### Installation ####

```
# Copy and edit .env file
$ cp .env.sample .env
$ vim .env

# starting containers (attached)
$ docker-compose up

# starting containers (dettached)
$ docker-compose up -d
```

Configure portainer on: http://127.0.0.1:9000
Configure wordpres on: http://127.0.0.1

