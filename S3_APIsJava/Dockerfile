FROM openjdk:8
EXPOSE 9000
RUN chmod 777 target
COPY target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]