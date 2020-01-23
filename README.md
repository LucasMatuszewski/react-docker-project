# React test App with Docker
following:
- https://mherman.org/blog/dockerizing-a-react-app/
- https://medium.com/swlh/dockerizing-a-react-application-with-docker-and-nginx-19e88ef8e99a
- repo: https://github.com/machariamuguku/Docker-React-Nginx/blob/master/docker-compose-prod.yml
- https://automationrhapsody.com/dockerize-react-application-with-a-docker-multi-staged-build/
- repo: https://github.com/llatinov/cypress-testing-framework
- https://github.com/StephenGrider/docker-react
- https://github.com/mrcoles/node-react-docker-compose
- https://github.com/LucasMatuszewski/Docker-Webpack-Course/blob/master/.dockerignore

## COMMANDS FROM DOCKER ONBOARDING:
> git clone https://github.com/docker/doodle.git

1. make a new build and tag it as cheers2019 in doodle repository (shared tag???).
    this command use Dockerfile from current folder.
> cd doodle/cheers2019 && docker build -t predict4u/doodle:cheers2019 .

2. run a code from this docker image:
> docker run -it --rm predict4u/doodle:cheers2019

3. on MINGW64 (git console on Windows) we have to prefix the command with *winpty*
> winpty docker run -it --rm predict4u/doodle:cheers2019

4. push image to online repo:
> docker login && docker push predict4u/doodle:cheers2019

* list all images:
> docker image ls

* list all containers (without --all shows only running containers):
> docker container ls --all

* Explore the Docker help pages by running some help commands:

> docker --help
> docker container --help
> docker container ls --help
> docker run --help

### winpty
is a Windows software package providing an interface similar to a Unix pty-master for communicating with Windows console programs
https://github.com/rprichard/winpty


# CRA
> This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
