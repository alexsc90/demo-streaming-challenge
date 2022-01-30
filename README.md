# demo-streaming-challenge

This repository contains the solution for the challenge to create a simple Netflix-style media browser full stack app. It's been separated in two submodules, one for the backend, and other for the frontend:

- [demo-streaming-API](https://github.com/alexsc90/demo-streaming-API).
- [demo-streaming-client](https://github.com/alexsc90/demo-streaming-client).

## Setup

Clone both submodules to a directory in your local machine. Once you've done this, run the following commands in your main directory:

```
cd demo-streaming-API
npm install

cd demo-streaming-client
npm install
```

> You'll need to have a LTS [Node](https://nodejs.org/en/) version installed to use *npm* package manager.

## Technologies

- Backend
  - [Node](https://nodejs.org/en/)
  - [Express](expressjs.com/es/4x/api.html) v.4.17.2
  - [Graphql](https://graphql.org/) v.16.3.0
  - [apollo-server-expres](https://www.apollographql.com/docs/apollo-server/) v.3.6.2

- Frontend
  - [React](https://reactjs.org/docs/getting-started.html) v.17.0.2
  - [apollo/client](apollographql.com/docs/react/) v.3.5.8
  - [Bootstrap](https://getbootstrap.com/) v.5.1.3
  
## Usage

Once you have installed all dependencies, you'll have to run `` npm start `` on the root of each individual subdirectory. 

\* Make sure you have the API running before you start the frontend. 

You can see the UI on localhost:3000.

If you want to see the data being sent from the server to the frontend, you can go to localhost:4000/api/titles, or if you'd like to query your data from the apollo playground, go to localhost:4000/graphql.
