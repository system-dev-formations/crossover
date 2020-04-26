# Icinga2 install 

```shell script
  cd icinga2/
  docker build -t icinga2 .
  docker images
  docker run -d --name monitor -it -h icinga2 -p 17000:80 icinga2
  docker ps
  docker logs monitor
  docker ps
  docker exec monitor
  docker exec -it monitor /bin/bash
  docker ps
