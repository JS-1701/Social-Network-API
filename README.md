# Social Network API

## Description
The **Social Network API** is a backend application designed for a social network web app where users can share their thoughts, react to friends' thoughts, and maintain a friend list. Built with **Express.js**, **MongoDB**, and **Mongoose**, this API provides a robust foundation for managing social interactions in a scalable and efficient manner.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Technologies Used](#technologies-used)
- [Contribution](#contribution)
- [License](#license)

## Installation
To install and run the application locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/social-network-api.git
   ```
2. Navigate to the project directory:
   ```sh
   cd social-network-api
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the application:
   ```sh
   npm start
   ```
   *(or use `nodemon` for automatic restarts during development: `npm run dev`)*

## Usage
This API allows users to:
- Create, read, update, and delete users.
- Add and remove friends.
- Create, read, update, and delete thoughts.
- React to thoughts and remove reactions.

To test the API, you can use **Insomnia**, **Postman**, or a similar API testing tool.

## API Routes

### Users
- `GET /api/users` - Get all users
- `GET /api/users/:id` - Get a single user by ID
- `POST /api/users` - Create a new user
- `PUT /api/users/:id` - Update a user by ID
- `DELETE /api/users/:id` - Delete a user by ID
- `POST /api/users/:userId/friends/:friendId` - Add a friend
- `DELETE /api/users/:userId/friends/:friendId` - Remove a friend

### Thoughts
- `GET /api/thoughts` - Get all thoughts
- `GET /api/thoughts/:id` - Get a single thought by ID
- `POST /api/thoughts` - Create a new thought
- `PUT /api/thoughts/:id` - Update a thought by ID
- `DELETE /api/thoughts/:id` - Delete a thought by ID
- `POST /api/thoughts/:thoughtId/reactions` - Add a reaction to a thought
- `DELETE /api/thoughts/:thoughtId/reactions/:reactionId` - Remove a reaction

## Technologies Used
- **Node.js** - JavaScript runtime environment
- **Express.js** - Backend web framework for Node.js
- **MongoDB** - NoSQL database for storing social network data
- **Mongoose** - ODM (Object Data Modeling) library for MongoDB
- **JavaScript Date Object** - Used for timestamp formatting

## Walkthrough Video
A walkthrough video demonstrating the API functionality can be found here: 
[Watch the walkthrough video](#) *(Replace `#` with your actual video link)*

## Contribution
Thanks to **OpenAI** and my **classmates** for their help and guidance in with this project.

## License
This project is licensed under the [MIT License](LICENSE).



