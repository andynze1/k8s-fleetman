FROM amazoncorretto:17.0.5-al2022-RC-headless

MAINTAINER Richard Chesterwood "contact@virtualpairprogrammers.com"

ADD target/positionreceiver-0.0.1-SNAPSHOT.jar webapp.jar

EXPOSE 8080

CMD ["java","-Xmx50m","-jar","webapp.jar"]
