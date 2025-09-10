FROM openjdk:11-jre
ENV SPRING_PROFILES_ACTIVE docker
COPY ./target/*.jar /app.jar
EXPOSE 9090
CMD ["java", "-jar","/app.jar"]