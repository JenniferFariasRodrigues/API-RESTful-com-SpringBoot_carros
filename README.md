<p align="center">
 <img src="https://www.pngitem.com/pimgs/m/108-1085187_free-cars-hd-png-download.png" height="200" width="250">  
 <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Automobile_PNG_Photo.png/800px-Automobile_PNG_Photo.png" height="200" width="250"> 
 <img src="https://static.vecteezy.com/system/resources/previews/001/199/360/non_2x/classic-car-png.png" height="200" width="250">
</p>

<h1 align="center"> Carros API </h1>
<p align="center">A RESTful API for managing car-related data, built with Java and Spring Boot.</p>

---

### Description

The **Carros API** is a backend project developed using Java and Spring Boot. It provides endpoints for managing a database of cars, including operations such as retrieving, adding, updating, and deleting car records. This project is designed as a scalable and maintainable solution for car inventory or dealership management systems.

---

## **Technologies Used**

- **Java**: Primary programming language for the backend logic.
- **Spring Boot**: Framework used for building the REST API.
- **Maven**: Dependency management and project build tool.
- **H2 Database**: Embedded database for development and testing.
- **JUnit**: Framework for unit testing.
- **Postman**: Suggested for API testing and interaction.

---

### Getting Started

#### Prerequisites

- **Java 11+**
- **Maven 3.6+**

#### Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/carros-api.git

Navigate to the project directory:

Copiar código
cd carros
Build the project:

Copiar código
./mvnw clean install
Run the application:

Copiar código
./mvnw spring-boot:run

Access the API documentation:
Open your browser and go to http://localhost:8080/swagger-ui/.

API Endpoints
Base URL: /api/v1/cars

1. Get All Cars
Method: GET
Endpoint: /
Response: List of cars.

3. Add a New Car
Method: POST
Endpoint: /
Body:
json
Copiar código
{
  "brand": "Toyota",
  "model": "Corolla",
  "year": 2021
}
Response: Details of the created car.

5. Update a Car
Method: PUT
Endpoint: /{id}
Body:
json
Copiar código
{
  "brand": "Toyota",
  "model": "Corolla",
  "year": 2022
}
Response: Details of the updated car.

7. Delete a Car
Method: DELETE
Endpoint: /{id}
Response: 204 No Content.
Project Structure
css
Copiar código
carros/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.carros/
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       └── repository/
│   │   └── resources/
│   │       ├── application.properties
│   └── test/
│       └── java/
│           └── com.example.carros/
├── pom.xml
└── README.md
Contribution
Feel free to contribute to this project by submitting pull requests. Make sure your changes are well-documented and pass all tests before submission.

License
This project is licensed under the MIT License - see the LICENSE file for details.



