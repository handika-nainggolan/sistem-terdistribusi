# 🛒 Distributed E-Commerce System

An event-driven e-commerce platform built with microservices architecture using Apache Kafka, MongoDB, and Express.js. This project demonstrates scalable order processing, asynchronous communication, and distributed system design.

## 🚀 Features

- Microservices-based architecture
- Event-driven communication with Apache Kafka
- Order processing workflow
- Payment service integration
- Inventory management
- MongoDB database
- RESTful APIs with Express.js
- Dockerized services

## 🏗️ Architecture

```text
Client
   |
   v
Order Service
   |
   v
Apache Kafka
   |
   +--> Payment Service
   |
   +--> Inventory Service
   |
   +--> Notification Service
```

## 🛠️ Tech Stack

- Node.js
- Express.js
- Apache Kafka
- MongoDB
- Docker
- Docker Compose

## 📂 Project Structure

```text
.
├── order-service
├── payment-service
├── inventory-service
├── notification-service
├── docker-compose.yml
└── README.md
```

## ⚙️ Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/distributed-ecommerce-system.git
cd distributed-ecommerce-system
```

Start the infrastructure:

```bash
docker-compose up -d
```

Run the services:

```bash
npm install
npm start
```

## 🔄 Event Flow

1. Order Service publishes `order-created`
2. Payment Service consumes event and processes payment
3. Inventory Service updates stock
4. Notification Service sends confirmation

## 📈 Future Enhancements

- Kubernetes Deployment
- GitHub Actions CI/CD
- Prometheus Monitoring
- Grafana Dashboard
- API Gateway
- Authentication & Authorization

## 👨‍💻 Author

**Handika Pratama Nainggolan**

GitHub: :handika-nainggolan
