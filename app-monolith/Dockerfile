FROM openjdk:8u171-jdk-alpine3.7
MAINTAINER Michał Michaluk <michal.michaluk@bottega.com.pl>

EXPOSE 8080
COPY target/app.jar app.jar
ENTRYPOINT ["java", "-jar","/app.jar", "--spring.profiles.active=docker"]
