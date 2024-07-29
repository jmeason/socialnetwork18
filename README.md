# Social Network API
The Social Network API is a backend application that allows users to share thoughts, react to friends' thoughts, and manage a friend list. It uses MongoDB as the database, with Mongoose for object data modeling. This API is built with Node.js and Express.js, providing a set of RESTful routes to interact with the data.
## API Endpoints
### Users
Users
GET /api/users - Get all users
GET /api/users/:id - Get a single user by ID
POST /api/users - Create a new user
PUT /api/users/:id - Update a user by ID
DELETE /api/users/:id - Delete a user by ID (and associated thoughts)
Thoughts
GET /api/thoughts - Get all thoughts
GET /api/thoughts/:id - Get a single thought by ID
POST /api/thoughts - Create a new thought
PUT /api/thoughts/:id - Update a thought by ID
DELETE /api/thoughts/:id - Delete a thought by ID

## Walkthrough video
[https://app.screencastify.com/v3/watch/IkHjl9iN8DsqwtD9p3bf] 
