# 🛠️ NM Cars – Backend API (Spring Boot)
This is the backend service for **NM Cars Auto Service**.  
Built with **Java + Spring Boot**, it provides API endpoints for managing services, appointments, customer data, and more (depending on your version).

✔ Java  
✔ Spring Boot  
✔ REST APIs  
✔ Spring Security  
✔ Database design  
✔ Clean architecture  

---
## ✨ Features (Depending on version)

- REST API endpoints  
- CRUD operations  
- Spring Boot architecture  
- Spring Web  
- Spring Data JPA  
- MySQL/PostgreSQL support  
- Service/Repository pattern  
- DTO & Entity separation  
- Validation  
- Exception handling  
- CORS configuration   

---
## 🧱 Tech Stack
- **Java 17+**  
- **Spring Boot 3.x**  
- **Spring Web**  
- **Spring Data JPA**  
- **H2 / PostgreSQL / MySQL**  
- **Lombok**  

---

## 📂 Project Structure
src/
├── main/
│ ├── java/com/nmcars/
│ │ ├── controller/
│ │ ├── service/
│ │ ├── repository/
│ │ ├── model/
│ │ ├── dto/
│ │ └── NMcarsApplication.java
│ └── resources/
│ ├── application.properties
│ └── data.sql (optional)

---

## 🚀 Run Locally

### Clone the repository
```bash
git clone https://github.com/LAdamyan/NM-Cars-Backend
cd NM-Cars-Backend

Build the project
mvn clean install

Run the backend
mvn spring-boot:run

🔧 Configuration (application.properties example)
server.port=8080

spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


For MySQL:

spring.datasource.url=jdbc:mysql://localhost:3306/nmcars
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

📡 Example API Endpoints
Get all services
GET /api/services

Add new service
POST /api/services
Body: { "name": "Grote onderhoudsbeurt" }

Get appointment list
GET /api/appointments

Root endpoint
GET /api/health
Response: "Backend is running"

🗄️ Database

Supports:

H2 (in-memory)
MySQL
PostgreSQL

📞 Contact

Developer: Lilit Adamyan
📧 Email: lilitadamyan2017@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/lilit-adamyan-213a71102/
💻 GitHub: https://github.com/LAdamyan

⭐ Give this repo a star!
