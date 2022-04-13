# dev-to-mern-cloudinary

# 🚀 Javascript full-stack 🚀

## MERN Stack

### React / Express / MongoDB / Redux

https://github.com/coding-to-music/dev-to-mern-cloudinary

https://dev-to-mern-cloudinary.herokuapp.com

by Eknoorpreet Singh https://github.com/eknoorpreet

https://github.com/eknoorpreet/dev.to-clone

<h1 align="center">
  <br>
  <a href="https://devfrom.netlify.app"><img src="https://res.cloudinary.com/practicaldev/image/fetch/s--QG4or-x4--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/jrzutxzs0l43wqvw5k8z.png" alt="DEV.to Clone" width="200"></a>
  <br>
  <br>
  <b>DEV.to Clone</b>
  <br>
</h1>

[![Netlify Status](https://api.netlify.com/api/v1/badges/c804d244-6f9d-4e37-be5d-3a8f5bd4e414/deploy-status)](https://app.netlify.com/sites/devfrom/deploys)

[![forthebadge](https://svgshare.com/i/fcr.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

> An DEV.to clone created with MongoDB, Express, React, Node, and Socket.io

![](screenshots/cover.png)

## [Live Site](https://devfrom.netlify.app)

## [Backend API](https://devfrom.herokuapp.com/)

## Tech

- UI: <a href="https://github.com/facebook/react">React</a>
- Routing: <a href="https://github.com/ReactTraining/react-router">React Router</a>
- Real-time Notifications: <a href="https://github.com/socketio/socket.io">Socket.io</a>
- Backend: <a href="https://github.com/expressjs/express">Express</a>
- Database: <a href="https://github.com/mongodb/mongo">MongoDB</a>
- ORM: <a href="https://github.com/Automattic/mongoose">Mongoose</a>
- Image hosting: <a href="https://cloudinary.com/">Cloudinary</a>

## Features

- Login / Signup
- Google / Facebook / Twitter / GitHub OAuth
- Create / Remove / Update / Delete Post
- Like / Unicorn / Bookmark Post
- Reading List
- Create / Add Tags to Post
- Follow Tags
- Find Posts by Tags
- Comment / Replies
- Like Comment
- Edit / Delete Comment
- View Profile
- Edit Profile
- Follow User
- Search Posts
- Real-time Notifications
- Skeleton Loading

## How to setup locally

### Clone

Clone the repo to your local machine using `https://github.com/eknoorpreet/dev.to-clone`

### Setup

Install npm dependencies in both `client` and `server` subdirectories using `npm install`

```shell
$ cd server && npm install
$ cd client && npm install
```

Set up a MongoDB database either locally or online via <a href='https://www.mongodb.com/cloud/atlas'>MongoDB Atlas</a>

Create a <a href="https://cloudinary.com/">Cloudinary account</a>

Create a new project on <a href='https://console.cloud.google.com'>Google Cloud Platform</a>

Create a `.env` file in in both `client` and `server` subdirectories

Set up the following environment variables

In `client/.env`:

```js
REACT_APP_BASE_URL=http://localhost:5000/api
REACT_APP_SOCKET_IO_URL=http://localhost:5000
REACT_APP_GOOGLE_CLIENT_ID=<GOOGLE_CLIENT_ID>
REACT_APP_GITHUB_CLIENT_ID=<GITHUB_CLIENT_ID>
REACT_APP_FB_APP_ID=<FACEBOOK_CLIENT_ID>
```

In `server/.env`:

```js
DB_USER = //user name for db
DB_PASSWORD = //password for db
DB_NAME = // name for db
JWT_KEY = //random string
COOKIE_KEY = //random string;
NODE_ENV = 'development';
CLIENT_URL = //the port of React app, ex: 'http://localhost:3000';

//cloundiary will provide you with the following credentials
CLOUDINARY_CLOUD_NAME = //cloud name
CLOUDINARY_API_KEY = //API key
CLOUDINARY_API_SECRET; //API secret

//Google will provide you with the following credentials
GOOGLE_API_KEY = //API key

//Github will provide you with the following credentials
GH_CLIENT_ID = //Github's Client ID
GH_CLIENT_SECRET = //Github's Client Secret

// Twitter will provide you with the following credentials
TWITTER_CONSUMER_KEY = //Twitter's Consumer key
TWITTER_CONSUMER_SECRET = //Twitter's Consumer Secret
```

Finally, run <code>npm start</code> in both `client` and `server` subdirectories

```shell
$ cd server && npm start
$ cd client && npm start
```

## Screenshots

### Login / Signup

![](screenshots/login-signup.gif)

### Like / Unicorn / Bookmark

![](screenshots/like-unicorn-bookmark.gif)

### New Post

![](screenshots/new-post.gif)

### Comments and Replies

![](screenshots/comments-replies.gif)

### Real-time Notifications

![](screenshots/notif.gif)

### Follow Tags

![](screenshots/tags.gif)

### Edit Profile

![](screenshots/edit-profile.gif)

### Search

![](screenshots/search.gif)

## About the Website: Maper

- A location-based website using React as Frontend and NodeJs, ExpressJS as backend, and MongoDB as Database. On this website, I had use MapBox for the world map and React-Mapbox-gl for configuration. We can select the place where we had visited and added the photo URL, so the entry will be seen on the map and in the visited place area. We can delete or modify the changes in the Entry we had created. It is a responsive website with live location of a point on the map. The Backend is deployed on Heroku and the frontend is deployed on Netlify.

#### The Password for the Entry: maper01

## Technology Stack

- React js
- Node js
- Express js
- MongoDB
- MapBox, React Mapbox-gl
- Heroku
- Netlify
- Flexbox
- Material-ui

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

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/dev-to-mern-cloudinary.git
git push -u origin main
```

## Heroku

```java
heroku create dev-to-mern-cloudinary
```

## Heroku MongoDB Environment Variables

```java
heroku config:set


heroku config:set MONGODB_URI="mongodb+srv://<userid>:<password>@cluster0.zadqe.mongodb.net/dev-to-mern-cloudinary?retryWrites=true&w=majority"
heroku config:set PASSWORD="something-secret"

heroku config:set PUBLIC_URL="https://dev-to-mern-cloudinary.herokuapp.com"
```

## Push to Heroku

```java
git push heroku

# or

npm run deploy
```

### Heroku Buildpack

See this repo for more info about setting up a node/react app on heroku:

https://github.com/mars/heroku-cra-node

```java
heroku buildpacks

heroku buildpacks --help

heroku buildpacks:clear

```

```java
heroku buildpacks
```

Output:

```java
=== dev-to-mern-cloudinary Buildpack URL
heroku/nodejs
```

### Notice we are doing a SET and then and ADD

```java
heroku buildpacks:set heroku/nodejs

heroku buildpacks:add mars/create-react-app
```

Output:

```java
Buildpack added. Next release on dev-to-mern-cloudinary will use:
  1. heroku/nodejs
  2. mars/create-react-app
Run git push heroku main to create a new release using these buildpacks.
```

### Lets try reversing the order

```java
heroku buildpacks:set mars/create-react-app

heroku buildpacks:add heroku/nodejs
```

```java
heroku buildpacks
```

Output:

```java
=== dev-to-mern-cloudinary Buildpack URL
heroku/nodejs
```

### Push to Heroku

```
git push heroku
```

## Error:

```java
2022-04-09T03:12:56.076028+00:00 app[web.1]: ls: cannot access '/app/build/static/js/*.js': No such file or directory
2022-04-09T03:12:56.076252+00:00 app[web.1]: Error injecting runtime env: bundle not found '/app/build/static/js/*.js'. See: https://github.com/mars/create-react-app-buildpack/blob/master/README.md#user-content-custom-bundle-location
2022-04-09T03:12:56.253505+00:00 app[web.1]: Starting log redirection...
2022-04-09T03:12:56.253698+00:00 app[web.1]: Starting nginx...
```

Attempted this:

```java
heroku config:set JS_RUNTIME_TARGET_BUNDLE=./client/build/static/js/*.js

heroku config:set JS_RUNTIME_TARGET_BUNDLE=/build/static/js/*.js

# and to remote it:

heroku config:unset JS_RUNTIME_TARGET_BUNDLE

```

## update npm packages

```java
npm install -g npm-check-updates
```

Output:

```java
removed 3 packages, changed 263 packages, and audited 264 packages in 10s

29 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```

```java
ncu -u
```

Output:

```java
Upgrading /mnt/volume_nyc1_01/dev-to-mern-cloudinary/package.json
[====================] 15/15 100%

 axios                ^0.21.0  →  ^0.26.1
 bcrypt                ^5.0.0  →   ^5.0.1
 body-parser          ^1.19.0  →  ^1.20.0
 cookie-parser         ^1.4.5  →   ^1.4.6
 dotenv                ^8.2.0  →  ^16.0.0
 express              ^4.17.1  →  ^4.17.3
 express-fileupload    ^1.2.0  →   ^1.3.1
 js-cookie             ^2.2.1  →   ^3.0.1
 mongoose            ^5.10.13  →  ^6.2.10
 nodemon               ^2.0.6  →  ^2.0.15
 reactjs-popup         ^2.0.4  →   ^2.0.5
 validator           ^13.1.17  →  ^13.7.0

Run npm install to install new versions.
```

```java
npm install
```

Output:

```java
added 58 packages, removed 42 packages, changed 89 packages, and audited 299 packages in 7s

32 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```

## Client directory

```java
cd client

ncu -u
```

```java
Upgrading /mnt/volume_nyc1_01/dev-to-mern-cloudinary/client/package.json
[====================] 18/18 100%

 @testing-library/jest-dom     ^5.11.4  →  ^5.16.4
 @testing-library/react        ^11.1.0  →  ^13.0.0
 @testing-library/user-event  ^12.1.10  →  ^14.0.4
 axios                         ^0.21.0  →  ^0.26.1
 dotenv                         ^8.2.0  →  ^16.0.0
 js-cookie                      ^2.2.1  →   ^3.0.1
 node-sass                     ^4.14.1  →   ^7.0.1
 react                         ^17.0.1  →  ^18.0.0
 react-dom                     ^17.0.1  →  ^18.0.0
 react-redux                    ^7.2.2  →   ^7.2.8
 react-router-dom               ^5.2.0  →   ^6.3.0
 react-scripts                   4.0.0  →    5.0.0
 reactjs-popup                  ^2.0.4  →   ^2.0.5
 redux                          ^4.0.5  →   ^4.1.2
 redux-thunk                    ^2.3.0  →   ^2.4.1
 web-vitals                     ^0.2.4  →   ^2.1.4

Run npm install to install new versions.
```
