# Awesome-Pet-Store
Project Name: Awesome Petstore API

Objective: Develop a RESTful API for managing pet-related information using NestJS and PostgreSQL based on the OpenAPI 

Petstore specification: Swagger UI

## Functional Requirements:

### Authentication and Authorization:
 - Implement user authentication and authorization mechanisms.
 - Define roles (e.g., admin, user) with appropriate permissions.
 - Ensure that only authorised users can perform certain actions.
 - Use OKTA or something similar

### Pet Management:
- Create, read, update, and delete (CRUD) operations for pets.
- Each pet should have the following attributes: ID, name, category, status, and photo

### Category Management:
- CRUD operations for pet categories.
- Categories should have an ID and a name.

### Order Management:
- Create, read, update, and delete orders.
- Each order should contain the following information: ID, pet ID, user ID, quantity, status, and a timestamp.

### User Management:
- Register new users.
- Authenticate users.
- Users should have a unique username, email, and password.
- Users can update their profiles.

### Swagger Documentation:
- Generate Swagger/OpenAPI documentation for the API.
- Ensure that the documentation is up-to-date with the API endpoints and schemas.

### Database Integration:
- Use PostgreSQL as the database management system.
- Use ORM like TypeORM or Prisma
- Use code-first approach where the schemas are defined in the code
- Define and implement the database schema to store pet, category, tag, order, and user information.

## Non-Functional Requirements:
### Performance:
- Ensure that the API can handle a large number of requests efficiently.
- Implement caching mechanisms where appropriate to improve response times.

### Security:
- Implement best practices for securing the API, including input validation and protection against common vulnerabilities (e.g., SQL injection, XSS).

### Scalability:
- Design the application architecture to be easily scalable to accommodate future growth.

### Logging and Monitoring:
- Implement logging for tracking system events and errors.
- Set up monitoring to proactively identify and address issues.

### Testing:
- Develop unit tests and integration tests to ensure the reliability and correctness of the API.

### Deployment:
- Provide deployment instructions for deploying the application to a production environment.

### Error Handling:
- Implement clear and informative error messages for API consumers.
- Handle errors gracefully to prevent service disruptions.

### Technical Stack:
- Backend Framework: NestJS
- Database: PostgreSQL
- API Documentation: Swagger/OpenAPI
- Authentication: JWT (JSON Web Tokens)
- Deployment: Docker, Kubernetes (optional)

### Assumptions and Constraints:
- The project assumes access to a PostgreSQL database server.
- The API will be developed in TypeScript.
- Development will follow RESTful API best practices.

### Optional:
- Create docker-compose.yaml that is able to run the application + PostgreSQL and pgAdmin
- Create DB migrations and make use of them
- Create integration tests
- Create DB seeders for testing and for static data

These requirements serve as a starting point for your project. You can further break down these high-level requirements into more detailed user stories or tasks and involve your development team in the process to refine them. Additionally, you may need to consider specific business rules or customization required for your Awesome Petstore project.

