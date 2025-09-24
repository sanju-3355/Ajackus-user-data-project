# User Management Dashboard

### Objective
Develop a simple web application where users can view, add, edit, and delete user details from a mock backend API.

> Demo 
> Link :  https://chaithu-bookstore.netlify.app/

### Usage 

``` 
git clone <github repository link>  //to clone the github repository
npm install                         //to install all the dependencies required to run the application
npm start                           //to start the application
```  

## Requirements
### User Interface:
* Display a list of users with details such as ID, First Name, Last Name, Email, and Department.
* Provide buttons or links to "Add", "Edit", and "Delete" users.
* A form to input a new user's details or edit an existing user's details.
* Add pagination options to the page with 10, 25, 50, and 100 limits. Alternatively, you can implement infinite scrolling. 
* Add a filter popup allowing users to filter by first name, last name, email, and department.
* Implement search and sort
* Make the interface responsive.
### Backend Interaction:
* Use JSONPlaceholder, a free online REST API that you can use for demonstration and test purposes.
* Specifically, use the '/users' endpoint to fetch and manipulate user data.
### Functionality:
* View: Display all users by fetching data from the '/users' endpoint.
* Add: Allow adding a new user by posting to the '/users' endpoint. (Note: JSONPlaceholder won't actually add the user, but will simulate a successful response.)
* Edit: Allow editing of an existing user. This should involve fetching the current data for a user, allowing for edits, and then putting the updated data back via the API.
* Delete: Allow users to be deleted, by sending a delete request to the API.
### Error Handling & Validations:
* Handle scenarios where the API request might fail - show an error message to the user in such cases.
* Add client-side validation for the user input form.

## Guidelines

* Followed Github Guidelines
  * Made the commits often and made sure the commit messages are concise and specific
  * Included a README file for explaining the project setup, usage instructions, and any additional information
* Followed Clean Code Guidelines
* The repo is well-organized and easy to navigate 
  * Followed the [create-react-app] folder structure
* The Application handled all the errors
