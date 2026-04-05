FROM openjdk:17-jdk-slim

WORKDIR /app

COPY . .

RUN chmod +x mvnw && ./mvnw clean install

EXPOSE 8080

CMD ["java", "-jar", "target/*.jar"]