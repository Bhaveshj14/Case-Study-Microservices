FROM openjdk
LABEL maintainer ="abc@mail.com"
EXPOSE 8082
WORKDIR /app
COPY target/stuentservice.jar /app/studentservice.jar
ENTRYPOINT ["java", "-jar","course.jar"]