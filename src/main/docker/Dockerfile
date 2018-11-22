FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} app.jar
ARG DEPENDENCY=target/dependency

ENTRYPOINT ["java","-cp","app:app/lib/*","/app.jar"]
