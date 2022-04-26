FROM java:8

EXPOSE 8050

ADD target/web-0.0.1-SNAPSHOT.jar webapp-0.jar

ENTRYPOINT ["java","-jar","webapp-0.jar"]