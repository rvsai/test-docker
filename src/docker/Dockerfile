FROM openjdk:8-jdk-alpine
VOLUME /tmp
ARG JAR_FILE
COPY rundockertest.jar rundockertest.jar
ARG DEPENDENCY=target/dependency

ENTRYPOINT ["java","-cp","app:app/lib/*","/rundockertest.jar"]
