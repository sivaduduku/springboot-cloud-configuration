1. Generate docker image -> Go to each project directory and run command -> mvn compile jib:dockerBuild
2. To view existing docker images -> docker images
3. To run docker images -> go to folder docker-compose/profile-directory -> run command -> docker compose up -d
4. To stop running docker containers -> docker compose down
5. To check running containers -> docker ps
6. To push local docker images to remote docker -> docker image push docker.io/sivaduduku/springboot-cloud-config-server:v1
7. To pull docker image from remote docker hub -> docker pull sivaduduku/springboot-cloud-config-server:v1
8. To pull rabbitmq from remote docker hub -> docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.12-management
9. To run mysql docker image -> docker run -p 3307:3306 --name accountsdb -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=accountsdb -d mysql
10. To run radis image -> docker run -p 6379:6379 --name eazyredis -d redis
11. If you want to map localhost to real domain name use url -> https://console.hookdeck.com/

