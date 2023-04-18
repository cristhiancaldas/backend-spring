FROM openjdk:11-jdk-slim

ARG JAR_FILE=target/*.jar

COPY --from=build ${JAR_FILE} backend.jar

ENTRYPOINT ["java","-jar","backend.jar"]