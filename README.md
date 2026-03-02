# CTSE-LAB05: Microservices Lab

## Overview
This project demonstrates a **microservices-based system** implemented in **Node.js**, containerized with **Docker**, and orchestrated with **Docker Compose**.  
It includes:

- **Item Service** – Manages items
- **Order Service** – Manages orders
- **Payment Service** – Processes payments
- **API Gateway** – Routes requests to the correct microservice

All services communicate only through the API Gateway.  
## Technology Stack
- Node.js + Express
- http-proxy-middleware (API Gateway)
- Docker & Docker Compose
- JSON for request/response bodies
- Postman (for API testing)

- docker compose build
-docker compose up
