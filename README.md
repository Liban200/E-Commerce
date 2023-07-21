# Module 13 E-Commerce 


## Overview

This repository contains the back-end code for an e-commerce website, which aims to provide a competitive platform for an internet retail company. The back end is built using the latest technologies and utilizes Express.js and Sequelize to interact with a MySQL database.

## Table of Contents

- [Installation](#installation)
- [Database Setup](#database-setup)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the back end of the e-commerce website, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/e-commerce-backend.git`
2. Navigate to the project directory: `cd e-commerce-backend`
3. Install the required dependencies: `npm install`

## Database Setup

Before running the application, you need to set up the MySQL database and configure the environment variables. Follow these steps:

1. Create a `.env` file in the root of the project.
2. Add the following configuration information to the `.env` file:

```plaintext
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306
```

Replace `your_database_name`, `your_mysql_username`, and `your_mysql_password` with your actual MySQL database name, username, and password.

## Usage

To run the application and start the server, use the following command:

```bash
npm start
```

This will start the Express.js server and sync the Sequelize models to the MySQL database using the configurations provided in the `.env` file.

## API Routes

The back end of the e-commerce website provides the following API routes:

- `GET /api/categories`: Retrieve all product categories in formatted JSON.
- `GET /api/products`: Get all products in formatted JSON.
- `GET /api/tags`: Fetch all tags in formatted JSON.
- `POST /api/categories`: Create a new product category.
- `POST /api/products`: Add a new product.
- `POST /api/tags`: Create a new tag.
- `PUT /api/categories/:id`: Update an existing product category.
- `PUT /api/products/:id`: Update an existing product.
- `PUT /api/tags/:id`: Update an existing tag.
- `DELETE /api/categories/:id`: Delete a product category.
- `DELETE /api/products/:id`: Delete a product.
- `DELETE /api/tags/:id`: Delete a tag.

## Testing

The application can be tested using Insomnia or any API testing tool of your choice. Ensure you have performed the database setup and started the server before testing the API routes. Use the routes mentioned in the [API Routes](#api-routes) section for testing the functionality.

## Contributing

We welcome contributions to improve the e-commerce website back end. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make the necessary changes and commit them: `git commit -m "Add feature-name"`
4. Push the changes to your branch: `git push origin feature-name`
5. Create a pull request with a detailed description of the feature/fix.

## Credits

- Shihan (TA)
- Krishna (TA)
- https://www.youtube.com/watch?v=H16GUC9Svyk
-https://expressjs.com/en/guide/routing.html

## Additional Info

I was not able to fix the UPDATE Tag. My apologies

## Walkthrough Video

https://drive.google.com/file/d/1HFqEAtWzKxll3uD-Yx2E4vj37zb2ozRW/view

