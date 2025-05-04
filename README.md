Airbnb Clone Project

A full‑stack booking platform simulation modeled after Airbnb. Build scalable backend services, design relational schemas, secure APIs, and automate deployments in a collaborative team environment.

📚 Learning Objectives

Master GitHub workflows and team collaboration

Design robust Django + MySQL database schemas

Implement JWT/OAuth security for REST/GraphQL APIs

Configure CI/CD pipelines using Docker & GitHub Actions

Document and plan features with industry best practices

🛠️ Tech Stack

Backend: Django, Graphene (GraphQL)

Database: MySQL

CI/CD: Docker, GitHub Actions

Security: JWT, OAuth2, HTTPS

⚙️ Prerequisites

Python 3.9+ & pip

Docker & Docker Compose

Git & GitHub account

MySQL server

🚀 Setup & Run

git clone <repo-url> && cd airbnb-clone

Copy .env.example → .env and configure credentials

docker-compose up --build

python manage.py migrate && python manage.py runserver

Technology Stack

Django: Python web framework used to build the backend RESTful APIs and application logic.

Graphene (GraphQL): Library for creating and serving GraphQL schemas and queries for flexible data retrieval.

MySQL: Relational database management system for storing user data, bookings, and listings.

Docker: Containerization platform to package the application and its dependencies for consistent development and production environments.

GitHub Actions: CI/CD tool to automate testing, linting, and deployment workflows on every push or pull request.

JWT (JSON Web Tokens): Token-based authentication mechanism for stateless user sessions.

OAuth2: Authorization protocol to securely manage user permissions and third-party access.

HTTPS: Encrypted transport layer to secure all HTTP traffic between client and server.


🤝 Contributing

Fork repo, create feature branch, open a PR

Follow code style guide
