FROM openjdk:8-jdk-alpine
LABEL maintainer="burghard.britzke"

COPY target/gs-rest-service-0.1.0.jar /app.jar

ENV JAVA_OPTS=""
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar" ]