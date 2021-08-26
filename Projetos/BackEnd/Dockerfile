# etapa de build
FROM maven:3.8.2-openjdk-11-slim as buildstage
# copia apenas o pom.xml do projeto e baixa as dependencias
COPY pom.xml .
RUN mvn dependency:go-offline
# copia todos os arquivos do projeto e faz o build
COPY . .
RUN mvn clean package -DskipTests=true

FROM openjdk:11-jdk-slim
COPY --from=buildstage ./target/*.jar ./app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
