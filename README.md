# Microservices Project
This project contains the docker-compose file for running the microservices system that includes user, product,and order services.

Each microservice is a separate repository, which can be found through the links below:

- [User Service](https://github.com/mohamedadham/user-service)
- [Product Service](https://github.com/mohamedadham/Product-Service)
- [Order Service](https://github.com/mohamedadham/Order-service)
- [Graphql Gateway](https://github.com/mohamedadham/graphql-gateway)

The microservices communicate with each other through RabbitMQ message broker, and are accessed via a GraphQL API Gateway. Services are built with NestJS framework and TypeORM and Prisma for database access.

## Requirements
Docker and Docker Compose
Node.js and npm

## Running the System
To start the microservices system, follow these steps:

1. Clone this repository:
```
git clone https://github.com/username/microservices-project.git
```
2. Change into the project directory:
```
cd microservices-project
```
3. Start the system with docker-compose:
```
docker-compose up
```

4. The GraphQL API Gateway will be available at http://localhost:3000/graphql. You can use a GraphQL client to query the API.

## Development
For development, you will need to have Node.js and npm installed on your local machine. Then follow these steps:

1. Clone the individual microservices repositories.
2. Install the required dependencies for each microservice by running npm install in their respective directories.
3. Start the development server for each microservice with npm run dev.

## Contributing
If you would like to contribute to this project, please open a new issue or pull request in the individual microservices repositories.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

I hope this helps! Let me know if you have any further questions.
