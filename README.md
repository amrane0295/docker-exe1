docker-exe1

```shell

 docker run -it -v /MountPoint --name myalpes alpine /bin/ash
 docker commit test myalpine:v12 
 docker images
 docker export myalpine > myalpine.tar
 docker export myalpine > latest.tar
 docker images
 docker export myalpes > latest.tar
 docker -rm -f myalpine
 docker rmi -f  $(docker images -q)
 docker images
 cat latest.tar | docker import - myalpine:v12
 docker images
 docker images
 docker login -u "nabilamrane" -p "1598753cr"
 docker pull myalpine
 docker image tag myalpine:v12  nabilamrane/exercice1
 docker push nabilamrane/exercice1






````
