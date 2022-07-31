# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
Obvious first step is to ensure Github access to the repo.
Next, clone this repo to your local machine. 
`git clone <link>`
Install Docker and make sure it is setup correctly by running the following commands in your terminal window -
`docker -v` and `docker-compose -v`
Then in your terminal window, change working directory to the project root directory `Anything Market 8Y09N` and run `docker-compose up`
If docker is working correctly, the backend should be runnign and able to connect to the local database. Test by pointing your browser to `http://localhost:3000/api/ping`
Finally check the frontend and make sure its connected to the backend. If everything is working properly, you will be able to create a new user at `http://localhost:3001/register`
You're all set. 
