# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Start with installing [docker on your system](https://docs.docker.com/get-docker/)
- Verify docker is running on your system by running **docker -v** and **docker-compose -v**.
- Go to the root of the directory and run **docker-compose up**
- You can visit [this](http://localhost:3000/api/ping) to verify the backend is working.
- For frontend , visit [this](http://localhost:3001/register) , to make sure it is connected to the backend you should create a new user.

