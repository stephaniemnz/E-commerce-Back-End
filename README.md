# E-commerce-Back-End

## Description 
- This project provides a backend for an e-commerce site, handling products, categories, and tags to manage an inventory system efficiently. Built with Express.js and Sequelize, it connects to a MySQL database.

## Installation
1. Clone the repository to your local machine: 
- git clone https://github.com/stephaniemnz/E-commerce-Back-End.git
2. Navigate to the application directory:
- cd E-commerce-Back-End
- cd Develop
3. Install Dependencies
- npm install 
4. Set up your database by creating a .env file in the root directory with the following variables:
- DB_NAME='ecommerce_db'
- DB_USER=''
- DB_PW=''
5. 
6. In the terminal seed the database:
- npm run seed
7. Start server:
- npm start

## Usage
Once the server is running, you can use Postman or any similar tool to test the API endpoints:

- GET /api/categories: Fetch all categories.
- GET /api/categories/:id: Fetch a single category by ID.
- POST /api/categories: Create a new category.
- PUT /api/categories/:id: Update a category by ID.
- DELETE /api/categories/:id: Delete a category by ID.



## Contact
Github: https://github.com/stephaniemnz
