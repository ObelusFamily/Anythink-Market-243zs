# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

First install docker onto your computer by following the websites instructions.
After the inital set-up, verify docker is running by using the commands docker -v or docker-compose -v
Then run docker-compose up from the projects root directory to load the backend and frontend 

##Make Sure You're Connected
To ensure that your container is running smoothly test it by pinging localhost:3001/api/ping
