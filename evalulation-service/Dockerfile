FROM  openjdk:11
EXPOSE 8085 
ADD /target/evaluation-service-0.0.1-SNAPSHOT.jar evaluation-service.jar
ENTRYPOINT ["java", "-jar", "evaluation-service.jar"]