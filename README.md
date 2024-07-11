Go Microservices Architecture
A backend microservices architecture built with Go, utilizing Redis for data storage and the Chi router for HTTP routing.

Overview
This project demonstrates a scalable and maintainable microservices architecture in Go. It includes:

HTTP Server: Configurable port for serving API requests.
Redis Integration: Redis used for storing and managing order data.
Order Management: Endpoints for creating, reading, updating, and deleting orders.
Graceful Shutdown: Proper handling of OS interrupts for safe shutdown.
JSON Serialization: Orders are stored and transmitted in JSON format.

