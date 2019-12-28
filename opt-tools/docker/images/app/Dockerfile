FROM debian:latest

RUN mkdir /app \
	&& apt-get update \
	&& apt-get install openjdk-11-jre -y \
	&& apt-get install maven -y

WORKDIR /app

ENTRYPOINT mvn spring-boot:run

