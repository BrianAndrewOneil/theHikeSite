# The Hike Site
A place to share your adventures and see where other hikers have been.

**Link to project:** currently in search of a new hosting service, to be redeployed soon
Sample acct: jon@jon.com / password1

<img alt="image of web app" src="https://brianandrewoneil.github.io/TicTacToe/img/theHikeSite.png" width=50%>

## How It's Made

**Tech used:** HTML, CSS (Bootstrap), JavaScript, Node.js, Express, MongoDB

I built this social media platform to allow users to create an account and then post pics and descriptions of their hikes. There's a shared feed so that users can see everyone's hikes and can click into individual posts to read more, like, comment, etc.

## Optimizations
Future enhancements for this app will include allowing users to curate a list of their favorite hikes, and allowing posters to include multiple images of their hikes.

## Lessons Learned
This project was a deep dive into MVC architecture and features of express & middleware like nodemon, passport, cloudinary, multer, etc.

## To Run it Yourself
### Install

`npm install`

### Things to add

- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URL`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

### Run

`npm start`


