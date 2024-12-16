# Nodejs_Express_Postgresql_Docker_REST_API_Project
This is CRUD Rest API project build using Node.js Express, Postgresql running on docker container for user management.

# Steps to run the application...
1) Clone the repository using 
        git clone <repo_link>

2) Install the dependencies 
        npm install

3) Create your own environment variables file and save the following variables: 
   PORT
   DB_USER
   DB_HOST
   DB_DATABASE
   DB_PORT
   DB_PASSWORD

4) Start the application using command 
        npm run dev

# Core Learnings from this project 

# 1. Setting Up the Development Environment

Docker Integration:

Learned how to run PostgreSQL in a Docker container using docker-compose.

Managed container lifecycles using Docker commands (docker run, docker exec, docker-compose up).

Project Structure:

Designed a clean folder structure for scalability and maintainability.

Configured environment variables securely using dotenv.

# 2. Building the REST API

Express.js API Development:

Set up basic routes (/users) with HTTP methods: GET, POST, PUT, DELETE.

Implemented route controllers and middleware for validation and error handling.

CRUD Operations with PostgreSQL:

Established a connection using pg (node-postgres) library.

Wrote SQL queries for data manipulation (INSERT, SELECT, UPDATE, DELETE).

# 3. Key Backend Concepts Mastered

Authentication and Authorization:

Implemented JWT-based authentication.

Protected API routes using middleware.

Data Validation:

Used libraries like Joi for schema validation.

Ensured server-side input validation and response formatting.

Error Handling:

Created a centralized error-handling mechanism.

Handled database errors gracefully and returned meaningful error messages.

# 4. Best Practices and Industry Standards

Code Quality:

Followed best practices like separation of concerns and using services and repositories.

Maintained clean and readable code with ESLint and Prettier.

Version Control:

Managed project versioning using Git and GitHub.

Created meaningful commits and maintained a clear development history.

# 5. Deployment Readiness

Database Migrations:

Used tools like Knex.js or Sequelize for database migrations.

Automated the setup process for new environments.

Containerization for Production:

Learned to build Docker images using Dockerfiles.

Created multi-container setups with docker-compose for PostgreSQL and the Node.js API.

# 6. Advanced Concepts Explored

Testing:

Wrote unit and integration tests using Jest and Supertest.

Set up automated testing workflows.

API Documentation:

Documented API endpoints using Swagger/OpenAPI.

Monitoring and Logs:

Configured logging using Winston and monitored API performance.

# Final Thoughts

This project reinforced my understanding of full-stack API development using modern tools and best practices. Deploying a scalable, production-ready API taught me the importance of code organization, security, and deployment automation.