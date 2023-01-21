FROM maven as base
LABEL "Project"="EFT"
LABEL "AUTHOR"="Nikhil"
WORKDIR /app
COPY . .
RUN mvn clean install

FROM  openjdk:11.0.10-jre
LABEL "Project"="EFT"
LABEL "AUTHOR"="Nikhil"
WORKDIR /app
COPY --from=base /app/target/zuul-0.0.1-SNAPSHOT.jar /app
EXPOSE 9999
CMD ["java","-jar","zuul-0.0.1-SNAPSHOT.jar"]