FROM openjdk:17-jdk-slim
VOLUME /tmp
COPY target/identity-api.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
