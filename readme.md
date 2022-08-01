# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Steps to Run Application Locally - 

1. [Install Docker](https://docs.docker.com/get-docker/)
2. Verify Docker is ready by running  -

    ```
    docker -v
    docker-compose -v

    ```
3. Then, run ```docker-compose up``` up from the project root directory to load Anythink's backend and frontend
