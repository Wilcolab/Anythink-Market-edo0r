# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

At Anythink, our engineers work with a development environment that's hosted in the cloud called Github Codespace. No need to install anything on your own computer! It takes about a minute to boot. Once it's up and ready you can start working directly in the browser or use VS Code to connect to the codespace in the cloud. Go ahead and create your own [codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=557845410).

#### In the terminal Run:
```
docker-compose up
```

#### Run the Backend
Once docker-compose finishes loading up, the backend should be running and able to connect to the database. After the server is up, make sure you test it by pointing your browser to [this link](https://raoakif-silver-fiesta-w4xp9g7j5g2w64-3000.githubpreview.dev/api/ping)

#### Register youself through the Frontend
If everything is working properly, you’ll be able to create a new user on [this link](https://raoakif-silver-fiesta-w4xp9g7j5g2w64-3001.githubpreview.dev/register)

## Add Code Owners to the Repository

Add a File named `CODEOWNERS` with the code, at the root of directory:
```
# Following people are the code Reviewers
* @vanessa-cooper @carl-rattmann
```
