FROM openjdk:1.8
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} department-service.jar
ENTRYPOINT ["java","-jar","/department-service.jar"]
EXPOSE 9001