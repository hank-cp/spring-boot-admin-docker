# spring-boot-admin-docker
Docker Image for https://github.com/codecentric/spring-boot-admin

### Usage
#### Pull image from Docker Hub
```
docker pull hankcp/spring-boot-admin:1.5.7
```
#### Build image
```
./gradlew dockerBuildImage
```
#### Run in container
```
docker run --name spring-boot-admin -p 8080:8080 spring-boot-admin:1.5.7
```