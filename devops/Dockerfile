FROM openjdk:11-jre-slim
ARG VERSION

COPY ./target/spring-boot-2-hello-world-1.0.2-${VERSION}.jar /usr/local/lib/app.jar
ENTRYPOINT ["java","-jar","/usr/local/lib/app.jar"]