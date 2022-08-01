# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
Step 1 -> install docker from https://docs.docker.com/get-docker/ .
Step 2 -> after the installation, run the command "docker -v" & "docker-compose -v" to verify docker.
Step 3 -> go to the root directory and run the command "docker-compose up", This command will load the Anythings backend and frontend.
Step 4 -> test whether backend is working properly by runing http://localhost:3000/api/ping in your browser.
Step 5 -> similarly check for frontend by runing http://localhost:3001/register.

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
