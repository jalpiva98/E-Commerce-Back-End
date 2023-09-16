# E-Commerce Back-End

## Overview
The E-Commerce Back End is a web application that serves as the back end for an internet retail company's e-commerce website. It provides the necessary infrastructure to manage products, categories, and tags in a MySQL database using the Sequelize ORM (Object-Relational Mapping). This back end is designed to empower your e-commerce business by leveraging the latest technologies, allowing you to compete effectively in the online retail space.

## Features

## Installation
Clone the repository to your local machine.

git clone https://github.com/your-username/e-commerce-back-end.git
Navigate to the project directory.

cd e-commerce-back-end
Install the required dependencies.

npm install
Configure your database connection by creating an environment variable file (.env) in the root directory and specifying the following variables:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306
Create and seed the development database.

npm run seed
Start the server.
npm start

## Usage
Once the server is running, you can use API testing tools like Insomnia or Postman to interact with the API. The API provides routes for managing categories, products, and tags.

## API Routes

```md
GET /api/categories: Retrieve all categories.

GET /api/categories/:id: Retrieve a single category by its ID.

POST /api/categories: Create a new category.

PUT /api/categories/:id: Update an existing category by its ID.

DELETE /api/categories/:id: Delete a category by its ID.

GET /api/products: Retrieve all products.

GET /api/products/:id: Retrieve a single product by its ID.

POST /api/products: Create a new product.

PUT /api/products/:id: Update an existing product by its ID.

DELETE /api/products/:id: Delete a product by its ID.

GET /api/tags: Retrieve all tags.

GET /api/tags/:id: Retrieve a single tag by its ID.

POST /api/tags: Create a new tag.

PUT /api/tags/:id: Update an existing tag by its ID.

DELETE /api/tags/:id: Delete a tag by its ID.
```

## Technologies
This application is built with the following technologies:

Node.js: JavaScript runtime environment.
Express.js: Web application framework for Node.js.
Sequelize: Promise-based Node.js ORM for MySQL.
MySQL: Relational database management system.
dotenv: Environment variable management.
Insomnia: API testing tool for testing API routes.

## License
This project is licensed under the MIT License.

## Acknowledgments
This application was created as part of my coding bootcamp project.


## Repo
https://github.com/jalpiva98/E-Commerce-Back-End
