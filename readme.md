# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/).
2. In the terminal, verify Docker is installed by running `docker -v` and `docker-compose -v`.
3. `cd` to the project root directory and run `docker-compose up`.

   - If Docker is working correctly, the backend should be running and able to connect to your local database.

4. Test backend by pointing browser to [http://localhost:3000/api/ping](http://localhost:3000/api/ping).
5. If everything is working properly, you’ll be able to create a new user on [http://localhost:3000/api/ping](http://localhost:3001/register).
