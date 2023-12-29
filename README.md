# Express Middlewares Project

## Description

This project is a simple Express.js application demonstrating the use of middlewares. It includes a basic authentication system where users submit a password, and if correct, they are granted access to secret information.

## Key Learnings

-   **Middleware Implementation**: Learned how to create and use custom middleware in Express. This project uses a middleware function, `checkPassword`, to validate user input.
-   **State Management**: Understood the basics of managing state within an Express application. The variable `userIsAuthorised` is used to track the authentication status.
-   **HTML Forms and POST Requests**: Gained practical experience in handling form submissions using POST requests in Express, and how to retrieve form data using the `body-parser` middleware.
-   **Conditional Rendering Based on Authentication**: Learned how to serve different HTML content based on the user's authentication status.

## Installation

Clone the repository:

```shell
git clone https://github.com/lappemic/udemy-express-middlewares-project.git
cd udemy-express-middlewares-project
npm install
```

## Usage

Start the server:

```shell
node index.js
```

or

```shell
nodemon index.js
```

Navigate to `http://localhost:3000` and enter the password in the form. If the password is 'ILoveProgramming', you will be redirected to a page with secret information.

## Project Structure

-   `index.js`: Main server file with Express setup and middleware.
-   `public/index.html`: HTML file for the main page with a password form.
-   `public/secret.html`: HTML file displayed upon successful password entry.

## License

This project is open-source and available under standard MIT license.
