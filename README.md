Product Management APIs Spring Boot Project
This project is a Spring Boot implementation of backend APIs for managing products. It provides a set of RESTful APIs that enable users to add, view, and manage products categorized under various categories like Jewelery, Food, Sports, and Clothes.
Features
1.	Product Management: Users can add, view, and manage products in different categories.
2.	Category-Based Search: Users can filter and view products based on their category.
3.	Rating System: Products include a rating system with rates and count of reviews.
Technologies Used
•	Java 21
•	Spring Boot
•	Spring MVCz
•	Spring Data JPA
•	MySQL (as the database)
•	Maven (for dependency management)
APIs
Product APIs
1.	Add Product: Allows users to add a new product to the system.
2.	Get Products by Category: Allows users to fetch products based on a specific category.
Getting Started
To set up the project on your local machine, follow these steps:
1.	Clone the repository:
bash
git clone https://github.com/Coderhimanshu11/OA_Round
2.	Configure the database settings in the application.properties file.
3.	Build the project using Maven:
bash
mvn clean install
4.	Run the application:
bash
mvn spring-boot:run
5.	Access the application: The application will be accessible at http://localhost:8080.
Database Setup
This project uses MySQL as the database. 
1.	Install MySQL on local machine.
2.	Create a new database named assesment.
3.	Update the database configuration in the application.properties file with MySQL username and password.
API Endpoints
•	POST /product/add: Adds a new product to the database.
•	GET /product/Category/{Category}: Retrieves products by category (JEWELERY, FOOD, SPORTS, CLOTHS).
Acknowledgments
•	Spring Boot: For the robust framework.
•	MySQL: For the reliable database management system.
________________________________________

