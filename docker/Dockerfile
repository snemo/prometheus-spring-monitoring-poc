FROM adoptopenjdk/openjdk11:jdk-11.0.3_7-alpine

COPY application.jar app.jar
ENV PROFILE=dev

ENTRYPOINT java -Djava.security.egd=file:/dev/./urandom -jar /app.jar --spring.profiles.active=$PROFILE