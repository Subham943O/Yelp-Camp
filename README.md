# Yelp-Camp

YelpCamp is a campground reviewing website where users can create their own campgrounds or review others' campgrounds. It is created using Node.js, Express, and MongoDB.

## Live Demo 
https://yelp-camp-krish.onrender.com/

## Images

![Screenshot from 2023-06-11 19-20-22](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/73450db2-9ebc-4431-b8da-14045550789f)
![Screenshot from 2023-06-11 19-50-41](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/28a9e68d-e17a-4945-b53b-b73b6e9cbeb2)
![Screenshot from 2023-06-11 19-51-09](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/150fc573-8fe9-4a93-bdb6-ca8faf61b322)
![Screenshot from 2023-06-11 19-51-39](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/34e713b1-2c85-4be1-8ba5-8705180779b8)
![Screenshot from 2023-06-11 19-52-05](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/9b3cb30b-ee2a-4e69-8f3d-7ec76e46e8fd)
![Screenshot from 2023-06-11 19-53-11](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/38f742d0-9e93-4dd4-aff0-17a10749cf4a)
![Screenshot from 2023-06-11 19-52-40](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/b69aff2f-45c9-4611-8fea-1090440c776c)
![Screenshot from 2023-06-11 19-53-22](https://github.com/KrishKumar3004/Yelp-Camp/assets/114848156/ac9a2d8a-cd51-4c0c-9a53-0a92f6753c92)

## Features
* Authentication
  * User login with username and password
  * Admin sign-up with admin code
* Authorization
  * User cannot manage posts without being authenticated
  * User cannot edit or delete posts and comments created by other users
  * Admin can manage all posts and comments
* Manage campground posts
  * User can create, edit and delete posts and comments
  * User can search existing campgrounds by name
* Flash messages responding to users' interaction with the app
* Responsive web design

## Getting Started
### Clone or download this repository
```
git clone https://github.com/prakalpshakya31/Yelp-Camp.git
```
### Get mongoDB
```
Go to https://www.mongodb.com/
```
### Install dependencies
```
npm install
```
or
```
yarn install
```
### Running locally
```
Run mongod in another terminal and node app.js in the terminal with the project

Then go to localhost:3000
```
## Built With
### Front-end
* [ejs](https://ejs.co/)
* [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/)

### Back-end
* [Nodejs](https://nodejs.org/en/)
* [Express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](https://mongoosejs.com/)
* [Passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [passport-local-mongoose](https://www.npmjs.com/package/passport-local-mongoose)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

## Authors

- [Krish Kumar](https://github.com/KrishKumar3004)

## Acknowledgments

- Colt Steele's Bootcamp course
