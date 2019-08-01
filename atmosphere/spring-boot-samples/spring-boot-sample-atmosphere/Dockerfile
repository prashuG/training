FROM openjdk:8

COPY target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar /usr/src/myapp/atmosphere.jar

EXPOSE 8080

WORKDIR /usr/src/myapp

CMD ["java", "-jar", "atmosphere.jar"]
