FROM java:latest

MAINTAINER Geert Van Bastelaere <geert.van.bastelaere@gmail.com>

RUN mkdir -p /activiti

WORKDIR /activiti

ADD ../test-activiti-springboot/target/activiti-boot.jar ./activiti-boot.jar

EXPOSE 8080

CMD ["java", "-jar", "activiti-boot.jar"]
