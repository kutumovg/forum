# Forum Project
This project is a web-based forum application that enables user communication through posts and comments. Users can associate categories to posts, filter content, and express preferences through likes and dislikes.

## Objectives

<ul>
    <li>Enable communication between users via posts and comments.</li>
    <li>Allow categorization of posts.</li>
    <li>Support liking and disliking of posts and comments.</li>
    <li>Implement filtering of posts based on categories, created posts, or liked posts.</li>
    <li>Enable sign in or sign up.</li>
</ul>


## Features
### SQLite Database

The application uses SQLite for managing and storing data, including users, posts, comments, and categories. 

Basic database operations, such as SELECT, CREATE, and INSERT queries, are required.

To optimize your database, we recommend designing an entity relationship diagram.

## User Authentication
Users must register and log in to interact with the forum:

<ul>
    <li>Registration requires an email, username, and password.</li>
    <li>Returns an error if the email is already taken.</li>
    <li>Passwords should be encrypted before storage (Bonus).</li>
    <li>Login session uses cookies to maintain a single session per user, with a defined expiration.</li>
</ul>

## User Interaction

Post and Comment Creation:
<ul> 
    <li>Registered users can create posts and comments. Posts can be associated with categories.</li>
</ul>

Likes and Dislikes: 
<ul>
    <li>Registered users can like or dislike posts and comments. Totals are visible to all users.</li>
</ul>

## Filtering
A filtering mechanism allows users to filter posts by:

<ul>
    <li>Categories (Autobiography, Comedy, Science Fiction, Fantasy, Mystery, Other).</li>
    <li>Created posts (specific to logged-in users).</li>
    <li>Liked posts (specific to logged-in users).</li>
</ul>

## Docker Integration

This project is containerized with Docker:
<ul>
    <li>docker build -t forum .</li>
    <li>docker run -p 8080:8080 forum</li>
</ul>

## Technical Requirements

Database: 
<ul>
    <li>SQLite</li>
</ul>
Error Handling:
<ul> 
    <li>Manage both website errors (HTTP status) and technical errors.</li>
</ul>
Code Quality:
<ul> 
    <li>Follow best practices and maintain clean code.</li>
</ul>
Testing:
<ul> 
    <li>Include unit tests for critical functionalities.</li>
</ul>

Allowed Packages: All standard Go packages.

<ul>
    <li>sqlite3</li>
    <li>bcrypt</li>
    <li>UUID</li>
</ul>

Frontend Limitations: No frontend libraries (e.g., React, Angular, Vue) are allowed.

## Technologies Covered
This project will help you learn about:
Web Basics: HTML, HTTP, sessions, and cookies.
Docker: Setup, containerization, creating images, and managing dependencies.
SQL: Database management and manipulation.
Encryption: Basics of password encryption.

## Usage
<ul>
    <li>Make sure you have Go installed on your system.</li>
    <li>Clone this repository using your terminal:</li>

```
git clone git@git.01.alem.school:gkutumov/forum.git
```

<li>Navigate to the project directory:</li>

```
cd forum
```  
<li>Start the project:</li>

```
go run .
``` 
<li>Set Up Database:</li> 
Use SQLite to initialize the database tables for users, posts, comments, and categories.

<li>Run the Application:</li>
Access the forum locally to start posting and interacting!

</ul>

## Authors
<ul>
    <li>gkutumov</li>
    <li>ntoksano</li>
    <li>aamanzha</li>
</ul>

Thank you for using our Forum project! If you have any questions or feedback, feel free to reach out. Happy coding! 🚀