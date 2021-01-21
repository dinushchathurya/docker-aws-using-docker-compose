# Deploy simple To-Do App which created using Node.js, Express, MongoDb & ejs to AWS using Docker Compose


## Installation

1. Clone repo
2. run `npm install` 

## Run docker compose

1. run `docker-compose -f mongo.yaml up`

## Create Database

1. Navigate to `http://localhost:8081/`
2. Create Database & Collections

## Build Image

1. run `docker build -t my-app:1.0 .`

## Run Container

1. run `docker run my-app:1.0`

## Usage 

1. Navigate to `localhost:3000`