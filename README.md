# Workout Tracker

## Microservice functionality and tech:
### User authentication
- Authenticates user, hands over to user workout tracking
- Java, Spring Boot
### User workout tracking
- Includes functionality for adding new workouts and editing existing workouts, track progress for various exercises with graphs
- Fetches from database management microservice
- JavaScript, Node.js/Express.js
### Database management
- Implements CRUD operations for database, hands to workout catalog and user workout tracking
- JavaScript, Node.js, Mongoose, MongoDB -> DynamoDB
### Analytics
- Graph previous user exercise progression and provide deeper insight with future progress prediction with ML
- Achievements for accountability
- Python, Flask, TensorFlow
### APIs: 
- REST
### Containers and Orchestration: 
- Docker/Kubernetes

<!---

## Overview
Workout Tracker is a robust, modern application that allows users to track and monitor their workout progress. The application's main features include user authentication, workout tracking, database management, analytics, and achievements for user accountability. The application is built as a collection of microservices that work in unison to offer a seamless experience to end users.

## Tech Stack
Our application is built using various modern technologies to deliver the best performance and user experience. The technologies used are:

1. **Java** and **Spring Boot** for user authentication.
2. **JavaScript**, **Node.js**, and **Express.js** for user workout tracking.
3. **JavaScript**, **Node.js**, **Mongoose**, and **MongoDB -> DynamoDB** for database management.
4. **Python**, **Flask**, and **TensorFlow** for analytics and achievements.

## Microservices

### User Authentication
This microservice is responsible for user authentication. It verifies user credentials and passes the authenticated user to the user workout tracking microservice. This microservice is implemented using Java and Spring Boot.

### User Workout Tracking
This microservice includes functionality for adding new workouts, editing existing workouts, and tracking progress for various exercises with graphs. It fetches data from the database management microservice and is implemented in JavaScript using Node.js and Express.js.

### Database Management
This microservice implements CRUD (Create, Read, Update, Delete) operations for the database and is responsible for handling data for both the workout catalog and the user workout tracking microservice. The service is implemented in JavaScript, Node.js, and uses Mongoose for object modeling and MongoDB for data storage, which is further transferred to DynamoDB for better scalability and performance.

### Analytics
The analytics microservice uses Python, Flask, and TensorFlow to graph previous user exercise progression and provide deeper insights into the users' workout trends. It also utilizes machine learning for predicting future progress. 

## APIs
The application communicates between different services using REST APIs.

## Containers and Orchestration
To ensure the seamless functioning of our microservices and to handle the lifecycle of containers effectively, we use Docker for containerization and Kubernetes for orchestration. This combination helps us to scale our services up and down based on the demand, ensuring high availability and robust performance of our application.

## Getting Started
Instructions for setting up the local development environment for our application will be added soon. 

## Contribute
Feel free to submit issues and enhancement requests. We'd love to have your contributions to make this project better. 

## License
Details about the project license will be added soon.
-->
