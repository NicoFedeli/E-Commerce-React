## Overview 👓

This project implements a comprehensive E-Commerce platform specializing in electronic equipment. The product catalog focuses on high-demand categories: Phones, Tablets, Computers, and Televisions (TVs).

Key Features and Architecture:
Product Management: The system supports full Role-Based Access Control (RBAC) for product lifecycle management, including:

Creation of new products.

Modification of existing listings.

Deletion of products.

Authentication & Authorization: JSON Web Tokens (JWT) are utilized for robust and stateless management of user roles and permissions, ensuring secure access to protected routes and features.

Advanced Filtering: Users can efficiently navigate the extensive catalog using advanced filtering mechanisms.

Payment Integration: The platform implements various payment methods, enhancing user flexibility during checkout.

In essence, the project delivers a secure, role-managed, and feature-rich online marketplace for consumer electronics.
 

## Technologies 🖥️

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- React: Components, Props, Events, Hooks, Router, Axios
- Redux: Store, Reducers, Actions
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,
- Deployment: Heroku

## Run Locally 🏃‍➡️

### 1. Clone repo

```
$ git clone git@github.com:basir/node-react-ecommerce.git
$ cd node-react-ecommerce
```

### 2. Install MongoDB

Download it from here: https://docs.mongodb.com/manual/administration/install-community/

### 3. Run Backend

```
$ npm install
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- It returns admin email and password

### 6. Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin

### 7. Create Products

- Run http://localhost:3000/products
- Click create product and enter product info
