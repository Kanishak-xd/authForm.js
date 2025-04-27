# Node.js Express Authentication Application

This is a simple Node.js Authentication application built with Express.js and EJS templating engine. It provides basic user authentication functionality including signup, login, and logout features.

## Features

- User Registration (Sign Up)
- User Login
- Welcome Page for authenticated users
- Logout functionality
- Form validation
- Username uniqueness check

## Prerequisites

Before you begin, ensure you have the following installed:
- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kanishak-xd/authForm.js.git
   cd prac28
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the application**
   ```bash
   node app.js
   ```

4. **Access the application**
   Open your web browser and navigate to:
   ```
   http://localhost:3000/signup
   ```

## Project Structure

- `app.js` - Main application file containing routes and authentication logic
- `views/` - Directory containing EJS templates
  - `signup.ejs` - User registration form
  - `login.ejs` - User login form
  - `welcome.ejs` - Welcome page for authenticated users
- `package.json` - Project configuration and dependencies
- `node_modules/` - Directory containing installed dependencies

## Dependencies

- Express.js - Web framework for Node.js
- EJS - Embedded JavaScript templating engine
- Body-parser - Middleware for parsing request bodies

## Usage

1. Visit `/signup` to create a new account
2. After successful registration, you'll be redirected to the login page
3. Log in with your credentials
4. Upon successful login, you'll see a welcome page
5. Use the logout button to end your session

## Security Note

This is a basic authentication implementation for demonstration purposes. In a production environment, you should:
- Use secure password hashing
- Implement session management
- Use environment variables for sensitive data
- Add CSRF protection
- Use HTTPS

## License

ISC 