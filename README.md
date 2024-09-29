# RESTFUL Movies API<br/>
Overview<br/>
This project is a full-stack application that implements a RESTful Movies API using Node.js, Express, and MongoDB for the backend. The API supports CRUD operations for movie data and user authentication.

Features<br/>
CRUD Operations: Create, Read, Update, and Delete movie data.<br/>
Movie Querying: Filter movies by title, genre, and year.<br/>
User Authentication: Register and login users using JWT.<br/>
Rate Limiting: Prevent abuse by limiting the number of API requests.<br/>

# Tech Stack<br/>
## Backend:<br/>
Node.js<br/>
Express<br/>
MongoDB<br/>

## Other Libraries:<br/>
Axios for HTTP requests<br/>
Bcrypt for password hashing<br/>
JSON Web Tokens (JWT) for authentication<br/>
Helmet for security<br/>
Express Rate Limit for rate limiting<br/>

# Installation<br/>
Clone the repository:<br/>
 git clone https://github.com/rajat128/MovieBackGDG.git <br/>
  cd movies-api<br/>
# ENV<br/>
MONGO_URI=""<br/>
CORS_ORIGIN=*<br/>
JWT_SECRET=""<br/>
PORT=<br/>

# API Endpoints<br/>
User Registration: POST /api/users/register<br/>
User Login: POST /api/users/login<br/>
Get All Movies: GET /api/movies<br/>
Create a Movie: POST /api/movies<br/>
Update a Movie: PUT /api/movies/:id<br/>
Delete a Movie: DELETE /api/movies/:id<br/>
Filter Movies: GET /api/movies/filter<br/>

# Contributing<br/>
Contributions are welcome! Please create a pull request with your changes.<br/>
