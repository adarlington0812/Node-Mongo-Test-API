## How to Run

1. Run `npm install`
2. Configure `.env` with your MongoDB connection string (MONGODB_URL, PORT)
3. Start the server: `node server.js`
4. Access `GET /users/:id`

## Description

This API exposes a GET endpoint `/users/:id` that retrieves a user by their MongoDB `_id`, only if their age is greater than 21. It gracefully handles invalid ObjectId errors and returns 404 if the user is not found.
