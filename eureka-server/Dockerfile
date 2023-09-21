FROM openjdk
LABEL maintainer="abc@gmail.com"
EXPOSE 8761
WORKDIR /app
COPY target/eureka-server-0.0.1-SNAPSHOT.jar /app/eureka-server-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","eureka-server-0.0.1-SNAPSHOT.jar"]