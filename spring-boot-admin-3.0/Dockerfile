# Use this for buildx docker builds
FROM openjdk:17
EXPOSE 8080
COPY target/app.jar /maven/app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/maven/app.jar", "--spring.config.location=optional:file:/application.properties,optional:file:/application.yml,optional:classpath:application.yml"]