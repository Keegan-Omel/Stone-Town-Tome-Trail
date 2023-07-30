# Stone Town Tome Trail - MERN Book Search Engine (GraphQL Refactor)

## Table of Contents
- [Description](#description)
- [Getting Started](#getting-started)
- [Back-End Specifications](#back-end-specifications)
- [Front-End Specifications](#front-end-specifications)
- [Deployment](#deployment)
- [Screenshots](#screenshots)
- [Questions](#questions)

## Description
The Stone Town Tome Trail is a MERN Book Search Engine web application that allows users to search for new books to read and keep a list of books they wish to purchase. The application is built using the MERN stack with a React front-end, a GraphQL API powered by Apollo Server on the back-end, a MongoDB database, and Node.js/Express.js as the server.

## Getting Started
To run the application locally, follow these steps:

1. Clone the GitHub repository: [repository-link](https://github.com/Keegan-Omel/Stone-Town-Tome-Trail)
2. Install the required dependencies using `npm install`.
3. Start the development server using `npm start`.

## Back-End Specifications
In the back-end, you'll find the following important files that have been modified for the GraphQL API:

1. `auth.js`: The authentication middleware function has been updated to work with the GraphQL API.

2. `server.js`: The Apollo Server has been implemented and applied to the Express server as middleware.

3. Schemas directory:
   - `index.js`: This file exports typeDefs and resolvers.
   - `resolvers.js`: The query and mutation functionality has been defined to work with the Mongoose models.
   - `typeDefs.js`: The necessary Query and Mutation types have been defined, including User and Book types.

## Front-End Specifications
In the front-end, you'll find the following important files that have been created/modified for the GraphQL API:

1. `queries.js`: Contains the `GET_ME` query that executes the `me` query set up using Apollo Server.

2. `mutations.js`:
   - `LOGIN_USER`: Executes the `loginUser` mutation set up using Apollo Server.
   - `ADD_USER`: Executes the `addUser` mutation.
   - `SAVE_BOOK`: Executes the `saveBook` mutation.
   - `REMOVE_BOOK`: Executes the `removeBook` mutation.

3. Additional tasks have been completed in various front-end files, such as `App.js`, `SearchBooks.js`, `SavedBooks.js`, `SignupForm.js`, and `LoginForm.js`.

## Deployment
The application has been deployed to Heroku with a MongoDB database using MongoDB Atlas. You can access the live application here: [link-to-live-app](link-to-live-app)

## Questions
If you have any questions or need further assistance, please feel free to contact me.

Author: Keegan Omel

GitHub: [GitHub Link](https://github.com/Keegan-Omel/Stone-Town-Tome-Trail)