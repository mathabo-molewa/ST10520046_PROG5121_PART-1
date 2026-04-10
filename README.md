# Chat Application - Login System

## Project Description
This project is a simple Java-based login system.  
It allows a user to register and then log in using their details.

The system checks that the username, password, and phone number are in the correct format before allowing registration.

## Features

### 1. Username Validation
- Must contain an underscore (_)
- Must not be longer than 5 characters

### 2. Password Validation
The password must:
- Be at least 8 characters long
- Contain at least one capital letter
- Contain at least one number
- Contain at least one special character

### 3. Phone Number Validation
- Must start with +27 (South African format)
- Must be no more than 12 characters long

### 4. User Registration
- The system checks all inputs
- If all inputs are correct, the user is registered successfully
- If not, an error message is shown

### 5. User Login
- The user enters their username and password
- The system checks if the details match the registered user
- A success or failure message is displayed

---

## Project Structure

- `MainApp.java`
  - Handles user input and interaction
  - Controls the flow of the program

- `Login.java`
  - Contains all validation methods
  - Stores user data
  - Handles registration and login logic

- `LoginTest.java`
  - Contains unit tests using JUnit
  - Tests all methods in the Login class

---

## How to Run the Program

1. Open the project in NetBeans or any Java IDE
2. Run `MainApp.java`
3. Follow the instructions in the console:
   - Enter username
   - Enter password
   - Enter phone number
   - Then log in with your details.
