# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Install docker - https://docs.docker.com/get-docker/

Once installed open a terminal e.g, command prompt
Navigate to your git clone
Type docker-compose up to start the backend and connect to the database
test the backend with - http://localhost:3000/api/ping
test the frontend with - http://localhost:3001/register
then done.
