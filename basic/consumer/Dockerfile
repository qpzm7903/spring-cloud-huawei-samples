# 使用官方 Java 运行时作为父镜像
FROM openjdk:17-jdk-alpine
ARG JAR_FILE
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]