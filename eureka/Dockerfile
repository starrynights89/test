FROM alpine
MAINTAINER starrynights89
EXPOSE 8761
ADD build/libs/eureka-0.0.1-SNAPSHOT.jar eureka-0.0.1-SNAPSHOT.jar
RUN apk add --no-cache openjdk8
ENTRYPOINT ["java", "-jar", "eureka-0.0.1-SNAPSHOT.jar"]