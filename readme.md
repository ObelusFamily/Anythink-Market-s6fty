# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Create Github Workspace from Snack
Ness will give you the link, just click it.

2. Waiting for Codespace to boot and running

3. run `docker-compose up` on terminal

4. Make sure backend should be running and able to connect to the database.

    [https://your-codespace-url-3000.githubpreview.dev/api/ping](https://your-codespace-url-3000.githubpreview.dev/api/ping)

5. Check the frontend and make sure it’s connected to the backend

    [https://your-codespace-url-3001.githubpreview.dev/](https://your-codespace-url-3001.githubpreview.dev/)

6. If everything is working properly, you’ll be able to create a new user on sign up page.

