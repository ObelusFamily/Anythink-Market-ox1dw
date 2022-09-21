# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

For the First Setup you need to install Docker.
If it is installed you can verify by typing following in your terminal:
docker -v and docker-compose -v

Then you can load the Repo from the project root directory by typing following in your terminal:
docker-compose up

The next Step is testing by connecting to your local database by pointing your browser to:
http://localhost:3000/api/ping

If everthying is working properly you will be able to create a user:
http://localhost:3001/register
