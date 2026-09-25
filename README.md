
# Portfolio Analytics API

A high-performance RESTful API built with **Java 21** and **Spring Boot 3** designed to track investment portfolios, process multi-asset BUY/SELL transactions, and calculate real-time weighted cost basis, unrealised PnL, and asset allocations.

## Tech Stack
* **Language:** Java 21 (Records, Pattern Matching)
* **Framework:** Spring Boot 3 (Spring Web, Spring Data JPA, Spring Security)
* **Database:** PostgreSQL
* **Containerisation:** Docker & Docker Compose

## Key Features
* **Transaction Engine:** Handles BUY and SELL orders with strict balance and oversell validation.
* **Financial Analytics:** Computes weighted average purchase prices, nominal profit/loss, and portfolio asset weightings using precision `BigDecimal` arithmetic.
* **Tiered Architecture:** Clean separation of concerns (Controller → Service → Repository).
* **Security:** Stateless authentication using JWT and BCrypt password encryption.

## Getting Started
### Prerequisites
* Java 21 SDK
* Maven 3.9+
* Docker & PostgreSQL

### Running Locally
```bash
./mvnw clean spring-boot:run
