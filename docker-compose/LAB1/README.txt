>> To run executes following command

$ docker-compose up

>> To check docker images execute

$ docker image ls

>> To run service in background execute

$ docker-compose up -d

>> To see currently running services (use when you start the app with -d option)

$ docker-compose ps

>> To stop the running application service

$ docker-compose stop  ((use when you start the app with -d option)

>> To see the application environment e.g web

$ docker-compose run web env

>> bring everything down along with volumes

$ docker-compose down --volumes

