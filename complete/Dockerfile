FROM openjdk:8-jdk-alpine
LABEL description="Ein einfaches Sproing-Boot Beispiel"
COPY target/gs-rest-service-0.1.0.jar /app.jar
EXPOSE 8080/tcp
ENV JAVA_OPTS=""
ENTRYPOINT ["sh", "-c", "java $JAVA_OPTS -jar /app.jar" ]