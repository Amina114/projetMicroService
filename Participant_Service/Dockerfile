FROM openjdk:11
EXPOSE 8084
ADD target/participant-0.0.1-SNAPSHOT.jar participant.jar
ENTRYPOINT ["java" , "-jar" , "participant.jar"]  