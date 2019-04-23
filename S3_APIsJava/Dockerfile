FROM openjdk:8
EXPOSE 9000
ADD target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]