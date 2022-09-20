# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Launch docker on your computer. If docker is ready you can check by running the following commands.

`docker -v` and `docker-compose -v`

Then run `docker-compose up`

Once the docker image is up you can check by **pointing your browser** to [this link](http://localhost:3000/api/ping).

Then check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on [this link](http://localhost:3000/register).
