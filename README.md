# dockerinmotion

# Install
```
$ docker-machine create dockerinmotion
$ docker-machine env dockerinmotion
```
Create env file
```
$ cp .env .env.dist
```

Run the deployment
```
$ chmod u+x bin/deploy
./bin/deploy
```