FROM adoptopenjdk/openjdk11:alpine-jre
WORKDIR /app
ADD target/kanban-spring-server-0.0.1-SNAPSHOT.jar /app/app.jar
ENTRYPOINT ["java","-jar","app.jar"]
EXPOSE 8080