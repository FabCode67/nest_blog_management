<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>


#### This project is a Blog Management System designed to help the team learn NestJS fundamentals and advanced production-level concepts. The app will enable users to:
	1.	Create, read, update, and delete (CRUD) blog posts.
	2.	Tag posts with multiple categories.
	3.	Like posts, comment on them, and bookmark them for later reading.
	4.	Interact with real-time updates (e.g., notifications for likes and comments).
	5.	Manage user authentication and authorization with RBAC.


	5.	Manage user authentication and authorization with RBAC.

### Architecture Overview

The app will follow a modular architecture for scalability and maintainability:
1.	Backend (NestJS):
	•	Framework: NestJS for building scalable server-side applications.
	•	Database: PostgreSQL (via TypeORM or Drizzle ORM for ORM management).
	•	Caching: Redis for optimizing frequently accessed data.
	•	Real-Time Features: WebSockets for real-time notifications.
2.	Containerization:
	•	Docker for consistent environment setup across development and production.
3.	Deployment:
	•	Hosting platforms: Railway.app or Fly.io.
	•	CI/CD: GitHub Actions for automated testing, linting, building, and deployment.
4.	Development Workflow:
	•	Version control: GitHub for source code management.
	•	Automated quality checks: Linting (e.g., ESLint), formatting (Prettier), and testing pipelines.
