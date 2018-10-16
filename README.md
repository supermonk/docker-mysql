# docker-mysql
Simple docker for mysql with Flyway


##run command run multiple times if it takes time : docker-compose run flyway-service





##remove unused : docker ps -aq --no-trunc -f status=exited | xargs docker rm -f 

##Ref :
#https://8thlight.com/blog/dariusz-pasciak/2016/10/17/docker-compose-wait-for-dependencies.html 
#https://stackoverflow.com/questions/51670095/docker-flyway-mysql-8-client-does-not-support-authentication-protocol-requeste
#https://github.com/flyway/flyway-docker
#https://github.com/mysql/mysql-docker
