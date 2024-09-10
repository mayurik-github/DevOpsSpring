FROM eclipse-temurin:11
VOLUME /tmp
COPY ./target/myapp*jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]