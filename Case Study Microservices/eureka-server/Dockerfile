FROM openjdk
LABEL maintainer ="abc@mail.com"
EXPOSE 8083
WORKDIR /app
COPY target/course.jar /app/course.jar
ENTRYPOINT ["java", "-jar","course.jar"]