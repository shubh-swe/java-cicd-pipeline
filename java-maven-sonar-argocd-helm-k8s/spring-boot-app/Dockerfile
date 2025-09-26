FROM eclipse-temurin:11-jre-alpine   
WORKDIR /opt/app

ARG artifact=target/spring-boot-web.jar
COPY ${artifact} app.jar

EXPOSE 8080
ENTRYPOINT ["java","-jar","app.jar"]
