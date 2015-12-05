# Docker

Description :
  gradle spring boot application in Docker.

SETUP :
    Jdk version 1.7
    Gradle
    Docker
    
Build:
gradle buildDocker

Run:
docker run -it -p 80:8080 --name containername groupname/gs-spring-boot-docker
