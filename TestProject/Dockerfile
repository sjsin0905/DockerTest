FROM openjdk:17-jdk
LABEL maintainer="sjsin0905@naver.com"
ARG JAR_FILE=build/libs/TestProject-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} TestProject-springboot.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/TestProject-springboot.jar"]