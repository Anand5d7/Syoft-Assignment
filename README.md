# React Assignment - User Authentication and Dashboard

## Overview

This project is a simple web application built with React that includes three main pages:

1. **Sign Up Page**: Allows new users to register.
2. **Log In Page**: Allows existing users to log in.
3. **Dashboard Page**: Displays user information after successful login.

## Features

- User Registration
- User Login
- Dashboard displaying user details
- Form validation
- Responsive design

## Technologies Used

- React
- Axios (for making HTTP requests)
- React Router DOM (for navigation)
- CSS (for styling)

## Getting Started

Follow these instructions to set up the project locally.

### Prerequisites

Make sure you have Node.js and npm installed on your machine. You can download Node.js from [here](https://nodejs.org/).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Anand5d7/Syoft-Assignment.git
    ```

2. Navigate to the project directory:

    ```bash
    cd react-assignment
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the application:

    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to view the app.

### Project Structure

    react-assignment/
        │
        ├── public/
        │   ├── index.html
        │   └── ...
        │
        ├── src/
        │   ├── components/
        │   │   ├── SignUp.js
        │   │   ├── LogIn.js
        │   │   ├── Dashboard.js
        │   │   └── ...
        │   │
        │   ├── App.js
        │   ├── App.css
        │   ├── index.js
        │   └── ...
        │
        ├── package.json
        ├── README.md
        └── ...
### Usage

#### Sign Up
- Navigate to the Sign Up page.
- Fill in the required details (Full Name, Email, Password, Phone).
- Submit the form to create a new account.
  
#### Log In
- Navigate to the Log In page.
- Enter your registered Email and Password.
- Submit the form to log in.
#### Dashboard
- After logging in, you will be redirected to the Dashboard page.
- The dashboard displays your user information (excluding sensitive details).
### API Endpoints
#### Registration
- URL: https://syoft.dev/Api/user_registeration/api/user_registeration
- Method: POST
- Payload:
  ```bash
  {
      "user_firstname": "John",
      "user_email": "john@example.com",
      "user_phone": "1234567890",
      "user_password": "password123",
      "user_lastname": "Doe",
      "user_city": "Hyderabad",
      "user_zipcode": "500072"
  }
  ```
#### Login
- URL: https://syoft.dev/Api/userlogin/api/userlogin
- Method: POST
- Payload:
  ```bash
  {
      "user_email": "john@example.com",
      "user_password": "password123"
  }
  ```
### License
This project is licensed under the MIT License.

### Acknowledgments
- Thanks to the creators of React, Axios, and other libraries used in this project.
- Thanks to Syoft for providing the API endpoints for user registration and login.
### Screenshots

You can view screenshots of the application 

![Shopgracias-Weather Dashboard](https://github.com/Anand5d7/Shopgracias-Weather-App/assets/156296146/b398a57a-f760-4bfb-b070-b62f909380b8)

![Shopgracias-Weather Dashboard (2)](https://github.com/Anand5d7/Shopgracias-Weather-App/assets/156296146/8c38bd1b-7efd-4ba2-9ba1-9dd34f9e98a6)


### Live Demo

You can view a live demo of the application.

https://github.com/Anand5d7/Shopgracias-Weather-App/assets/156296146/fb75345e-4000-465f-b9ba-40eb9e1c8b2d

## Deployment

For more information on how to deploy your application, refer to the [Create React App deployment documentation](https://facebook.github.io/create-react-app/docs/deployment).

