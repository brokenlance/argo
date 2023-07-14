FROM brandonbenham/alpine-jdk-17:latest
COPY target/app-test-0.0.1-SNAPSHOT.jar artifact.jar
EXPOSE 8080
ENV MYSQL_HOST=192.168.1.141
ENTRYPOINT [ "java", "-jar", "artifact.jar" ]
