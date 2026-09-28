
FROM eclipse-temurin:21-jre

WORKDIR /Portfolio

COPY target/personalportfolio-0.0.1-SNAPSHOT.jar portfolio-v1.0.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "portfolio-v1.0.jar"]