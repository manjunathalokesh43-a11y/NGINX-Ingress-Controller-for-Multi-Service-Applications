# Trading API

A Spring Boot based Trading API application demonstrating CI/CD using Jenkins, Docker, GitHub, and Docker Hub.

## Tech Stack

* Java 21
* Spring Boot
* Maven
* Jenkins
* Docker
* Docker Hub
* AWS EC2

## CI/CD Flow

GitHub → Jenkins → Maven Build → Docker Build → Docker Hub Push → Deployment

## Build

mvn clean package

## Run

java -jar target/trading-api.jar

## Docker

docker build -t trading-api .

docker run -p 8080:8080 trading-api
