# RESTful-API-for-User-Data
This project is a simple RESTful API built with Node.js and Express. It allows users to retrieve information stored in a JSON file (`users.json`) through various endpoints.

Features:
Retrieve All Users: Get a complete list of users.
Fetch User by ID: Look up a specific user using their unique ID.
Filter Users by Profession: Find users based on their job title (e.g., developer, designer).
Search by Name: Retrieve a user's details by their name.
Error Handling: Provides meaningful error messages for invalid queries or missing data.

Technologies Used:
Node.js: Backend runtime environment.
Express: Web framework for creating the API.
File System Module (fs): Used to read and parse JSON files.

Endpoints:
1. Welcome Endpoint
Route: `/`
Method: GET
Description: Displays a welcome message.
Response: `"welcomeee!"`

2. List All Users
Route: `/users`
Method: GET
Descriptiion: Returns all users from the JSON file.

3. List Users Using their ID
Route: `/users/:id`
Method: GET
Descriptiion: Returns the user from the JSON file using that id. 

4. List Users Using their profession
Route: `/users/prefession/:profession`
Method: GET
Descriptiion: Returns all users from the JSON file with that profession.
