FROM java:8-jre

ADD ./target/spring-boot-kafka-consumer-example-0.0.1-SNAPSHOT.jar /usr/src/spring-boot-kafka-consumer-example-0.0.1-SNAPSHOT.jar

WORKDIR usr/src

ENTRYPOINT ["java","-jar", "spring-boot-kafka-consumer-example-0.0.1-SNAPSHOT.jar"]
