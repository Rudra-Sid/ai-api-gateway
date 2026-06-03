# AI API Gateway

## Project Goal

Build a high-performance API Gateway that:

* Receives incoming traffic
* Analyzes requests using AI
* Detects suspicious behavior
* Routes traffic to backend services
* Provides observability and monitoring

---

## Technology Stack

### Gateway

Language: Go

Responsibilities:

* Receive requests
* Validate requests
* Call AI Engine
* Route traffic
* Return responses

### AI Engine

Language: Python

Responsibilities:

* Analyze requests
* Calculate threat scores
* Detect anomalies

### DPI Engine (Future)

Language: C++

Responsibilities:

* Deep packet inspection
* High-performance traffic analysis

### Backend Service

Language: Go

Responsibilities:

* Provide application APIs
* Return business data

---

## MVP Architecture

Client
|
v
Gateway (Go)
|
+--> AI Engine (Python)
|
+--> Backend Service (Go)

---

## Future Architecture

Client
|
v
Gateway
|
+--> AI Engine
|
+--> DPI Engine
|
+--> Redis
|
+--> Kafka
|
+--> Monitoring Dashboard
|
+--> Backend Services

---

## Milestone 1

Objectives:

* Create Backend Service
* Create Gateway Service
* Create AI Engine
* Enable service-to-service communication
* Route first request successfully
