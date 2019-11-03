# node-starter
Boiler plate for setting up of a better architecture for a Node.js API

Project: Node Starter
Description: This app enables you to extend the CRUD functionalities of an API as you scale up.

## Getting Started

git clone the repo

### Prerequisites

MongoDB setup on your local environment

## Running the app
Cd into the node-starter folder

Install the dependencies

```node
npm install
```

Start server in development mode

```node
npm run dev:start
```

## Built With

*   [Express](https://expressjs.com/) - Express
*   [NodeJS](https://nodejs.org/) - NodeJS
*   [Mongoose](https://mongoosejs.com/docs/index.html) - Mongoose

## API Endpoints

### Versioning for the endpoints
*  `/api/`

*  Use `http://127.0.0.1:5000` as the base URL for the endpoints

## API Documentation
[Postman API Documentation](https://documenter.getpostman.com/view/6831940/SW14TwMS?version=latest)


| Method  | Description| Route |
| ------------- | ------------- | ------------- |
| GET |  Get all posts | `/api/post` |
| POST | Create a post | `/api/post` |
| GET |  Get a specific post | `/api/post/:id` |
| PUT |  Update a specific post | `/api/post/:id` |
| DELETE | Delete a specific post |`/api/post/:id` |

## Author

*   **Ryan Simiyu** 

