FROM openjdk:8u312-jdk
MAINTAINER Aditya Goel "adityagoel123@gmail.com"
EXPOSE 8080
WORKDIR /usr/local/bin/
COPY fleetman.jar webapp.jar
CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]