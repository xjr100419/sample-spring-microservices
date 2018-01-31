FROM 10.200.102.120/library/java8-alpine:0.0.1
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
ADD target/discovery-service.jar discovery-service.jar
ENTRYPOINT ["java", "-jar", "/discovery-service.jar"]
EXPOSE 8761