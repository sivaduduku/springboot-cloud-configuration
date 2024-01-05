1. Generate docker image -> Go to each project directory and run command -> mvn compile jib:dockerBuild
2. To view existing docker images -> docker images
3. To run docker images -> go to folder docker-compose/profile-directory -> run command -> docker compose up -d
4. To stop running docker containers -> docker compose down
5. To check running containers -> docker ps
6. To push local docker images to remote docker -> docker image push docker.io/sivaduduku/springboot-cloud-config-server:v1
7. To run mysql docker image -> docker run -p 3307:3306 --name accountsdb -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=accountsdb -d mysql
