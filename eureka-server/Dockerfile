FROM openjdk:8-jdk-alpine
COPY target/eureka-server-0.0.1-SNAPSHOT.jar /var/app/application.jar
ENTRYPOINT ["/usr/bin/java"]
CMD ["-jar", "/var/app/application.jar"]
VOLUME /var/app
EXPOSE 8761