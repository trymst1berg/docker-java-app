FROM openjdk:latest

ADD build/libs/*.jar app/
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app"]
