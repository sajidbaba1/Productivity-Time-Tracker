Productivity Time Tracker
A full-stack web application for tracking time and productivity, built with Next.js, Tailwind CSS, Kotlin, Spring Boot, GraphQL, and PostgreSQL.
Prerequisites

Java 17 (OpenJDK)
Node.js 18+
PostgreSQL 15
Redis
Docker
IntelliJ IDEA Ultimate
Git

Setup Instructions

Clone the repository:git clone https://github.com/sajidbaba1/Productivity-Time-Tracker.git


Open in IntelliJ IDEA Ultimate.
Configure .env file (see .env.example).
Run docker-compose.yml to start PostgreSQL and Redis.
Build and run the backend: ./gradlew bootRun
Install frontend dependencies: cd frontend && npm install
Start frontend: npm run dev

Features

User authentication (JWT, OAuth2)
Time tracking with tasks and projects
AI-powered document analysis
Analytics dashboard
Admin panel
