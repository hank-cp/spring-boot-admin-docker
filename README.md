[![](https://images.microbadger.com/badges/version/hankcp/spring-boot-admin.svg)](https://microbadger.com/images/hankcp/spring-boot-admin "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/hankcp/spring-boot-admin.svg)](https://microbadger.com/images/hankcp/spring-boot-admin "Get your own image badge on microbadger.com")

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
