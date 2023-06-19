# Use this for buildx docker builds
FROM openjdk:17.0.2
EXPOSE 8080
COPY target/app.jar /maven/app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/maven/app.jar", "--spring.config.additional-location=file:/application.properties,file:/application.yml"]

