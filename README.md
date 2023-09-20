# Book-Search-Engine

## Description
The goal of this project is to take starter code with a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. you set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API. you Modified the existing authentication middleware so that it works in the context of a GraphQL API. you created an Apollo Provider so that requests can communicate with an Apollo Server and deployed the application to Heroku with a MongoDB database using MongoDB Atlas.

## Install
Download the file from my github and install Insomnia!
* [Github Link](https://github.com/BryceedThompson/Employee-Tracker)

## Usage for local hosting
* Open your terminal in the root package.json
* Run the command 'npm i' 
* Run 'npm develop'

```md
GIVEN a book search engine
WHEN you load the search engine
THEN you are presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN you click on the Search for Books menu option
THEN you are presented with an input field to search for books and a submit button
WHEN you are not logged in and enter a search term in the input field and click the submit button
THEN you are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN you click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN you are presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN you are presented with two inputs for an email address and a password and login button
WHEN you enter a valid email address and create a password and click on the signup button
THEN my user account is created and you are logged in to the site
WHEN you enter my account’s email address and password and click on the login button
THEN you the modal closes and you are logged in to the site
WHEN you are logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN you are logged in and enter a search term in the input field and click the submit button
THEN you are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN you click on the Save button on a book
THEN that book’s information is saved to my account
WHEN you click on the option to see my saved books
THEN you are presented with all of the books you have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN you click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN you click on the Logout button
THEN you are logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  

```

## Deployed site
* [Deployed site](https://book-search11-5a9c6bb87475.herokuapp.com/)

## Contact
* [Github Link](https://github.com/BryceedThompson)
* [Contact Me via email](mailto:bryceedthompson@gmail.com)

## Credit
* [Apollo Docs on getting started with Apollo Server](https://www.apollographql.com/docs/apollo-server/getting-started)
* [Apollo Docs on integrating with Node.js middleware](https://www.apollographql.com/docs/apollo-server/integrations/building-integrations)
* [Apollo docs on handling arguments](https://www.apollographql.com/docs/apollo-server/data/resolvers#handling-arguments)
* [Vite docs on proxying API requests](https://vitejs.dev/config/server-options.html#server-proxy)
* [Apollo Docs on refetching queires with useMutation hook](https://www.apollographql.com/docs/react/data/mutations/#refetching-queries)

