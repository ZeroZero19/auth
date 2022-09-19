# Intro
Simple register & login to authenticate

Using Node.js, MongoDB (compass/atlas), [JWT](https://jwt.io/introduction)(for Authorization and Securely transmitting information), [Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
    
# Install
## Download code
    git clone https://github.com/ZeroZero19/auth.git
    cd auth

## Cloud
Require:    mongodb atlas, heroku

    heroku login
    heroku create
    git push heroku main    
    heroku ps:scale web=1
    heroku open

## Local
Require:    mongodb compass

    npm install
    npm start/node server.js

# Usage
## Mainpage
For Cloud   (`https://mysterious-river-91829.herokuapp.com/`)

For Local   (`http://localhost:9999/`)

## Include Registration, Login and ChangePassword pages

