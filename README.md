# Food-Ordering-App

## About The Project

### Purpose of the Project

The Food-Ordering-App project aims to simplify cafeteria management by providing a comprehensive system that allows Horel Owner owners an Peoples to effortlessly create, modify, and print invoices, add and manage products, and control user access.


## Key Features

### Admin Features

- Admin Dashboard
- Manage Categories (Add, Edit, Filter Products)
- Manage Products (Add, Edit, Delete, Filter Products)
- Manage Orders (Add)
- Manage Bills (View Bill Details, Download Bill, Cancel Bill, Filter Products)
- Manage Users (Ping User, Filter User)
- Change Password

### User Features

- Login & Sign Up
- User Dashboard
- Manage Orders (Add)
- Manage Bills (View Bill Details, Download Bill, Cancel Bill, Filter Products)
- Update Profile
- Change Password

### Built With

- Java (Spring Boot - Rest API)
- React.js
- MySQL Database

## Getting Started

### React Part

To run the React.js part, follow these steps:

1. Open your terminal in VS Code.
2. Set the `NODE_OPTIONS` environment variable with the command:
$env:NODE_OPTIONS = "--openssl-legacy-provider"
3. Start the React.js development server:
  npm start
4. Access the application in your web browser at [localhost:4200](http://localhost:4200).

### Spring Boot Part

To run the Spring Boot part, make sure it is accessible at [localhost:8082](http://localhost:8082). 

1. Sign up as a user.
2. Log in to obtain a user token, which is required for certain features.
3. Some features are accessible only with admin roles..

## Note

This project was created for Learning Full Stack Development
