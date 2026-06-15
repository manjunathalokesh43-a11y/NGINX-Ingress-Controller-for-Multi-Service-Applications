FROM eclipse-temurin:21-jdk

WORKDIR /app

COPY target/*.jar trading-api.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","trading-api.jar"]