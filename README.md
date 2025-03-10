# API Development Project

## Table of Contents
1. Introduction
2. Project Structure
3. Installation and Setup
4. Assignment Activities
   - Activity 1: XML, JSON & XQuery
   - Activity 2: PHP Product Management API
   - Activity 3: Online Store Category Management API
   - Activity 4: Project APIs Development
5. Testing & Documentation


## Introduction
This project involves developing multiple APIs using different technologies, including PHP, Laravel, and XML handling. The assignment covers fundamental API functionalities such as retrieving, creating, updating, and deleting resources. Additionally, it incorporates advanced features like nested set models and third-party API integration.

## Project Structure
The repository consists of the following directories:
- /activity1/ - Contains XML, JSON files, and XQuery expressions.
- /activity2/ - PHP-based Product Management API.
- /activity3/ - Laravel-based Category Management API.
- /activity4/ - Full-scale project API with third-party integrations and frontend.

## Installation and Setup
### Prerequisites:
- PHP (>= 8.0)
- Laravel (>= 9.x)
- MySQL Database
- Composer
- Postman (for testing APIs)
- Figma (for wireframe design)

### Setup Instructions:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo-link.git
   cd assignement4
   ```
2. Install dependencies:
   ```sh
   composer install
   ```
3. Set up environment variables:
   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
4. Configure database in .env file:
   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=online_store
   DB_USERNAME=root
   DB_PASSWORD=yourpassword
   ```
5. Run migrations:
   ```sh
   php artisan migrate
   ```
6. Start Laravel development server:
   ```sh
   php artisan serve
   ```
7. Test API endpoints using Postman or Swagger.

## Assignment Activities
### Activity 1: XML, JSON & XQuery
- Task: Create XML and JSON representations of student data.
- XQuery Expressions: Extract student name, age, and enrolled subjects.
- Files: Located in activity1/

### Activity 2: PHP Product Management API
- Endpoints:
  - GET /products - Retrieve all products
  - GET /products/{id} - Retrieve a product by ID
  - POST /products - Add a new product
  - PUT /products/{id} - Update product details
  - DELETE /products/{id} - Delete a product
- Files: Located in activity2/

### Activity 3: Online Store Category Management API
- Database Schema:
  - Table: categories (id, name, lft, rgt, created_at, updated_at)
- Endpoints:
  - GET /categories - Retrieve all categories (XML)
  - GET /categories/{id} - Retrieve a category by ID (XML)
  - POST /categories - Create a new category
  - PUT /categories/{id} - Update a category
  - DELETE /categories/{id} - Remove a category
- Files: Located in activity3/

### Activity 4: Project APIs Development
- Features:
  - Pivot tracker stories documented.
  - Wireframes designed using Figma.
  - APIs developed using Laravel.
  - Third-party API integration.
  - API testing using Postman/Swagger.
  - Frontend integrated with backend APIs.
- Files: Located in activity4/

## Testing & Documentation
- Use Postman or Swagger for testing API endpoints.
- Documentation is available in docs/.



