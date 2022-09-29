# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Instal Docker](https://docs.docker.com/get-docker/)
2. Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`
3. Run `docker-compose up` from the project directory to load Anythink's backend and frontend
4. Once the Docker container is running, test the backend with a ping to http://localhost:3000/api/ping
    - You should see a message like this `{"msg":"Pong! Seems like Everythink is working, great job!"}`
5. Now test the front end at http://localhost:3001/register
    - You can create an account on the local environment if you'd like