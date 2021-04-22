# Hacker-Ranking Web-project

A node and react powered web application.

##### Frontend Framework: React.js

##### Backend: Node.js

##### Language : Javascript

## Pages and Features

- Admin Panel with admin login and admin dashboard which shows all the hackers list
 (url is "/   admin-panel)  
- Home Page (url is "/")
- User Login (url is "/login")
- User Register (url is "/register")
- View Hackers (url is "/hackers")
- Hacker Detail (url is "/hacker/:id")
- Statistics Page (url is "/hacker/statistics")[Extra](Advanced)
- Easy interface

## Backend Features

- Authentication using passport.js and json web token
- main.js is main file for backend
- ranking system strategy in rankingSystem.js (updating database with new rank each 5 min)[/Backend/ratingSystem/ratingSystem.js]


#### Clone project in virtualenv

git clone [https://github.com/shivansh-rao/Foodshala](https://github.com/shivansh-rao/Foodshala)

#### Install all requirements

For Frontend

- go to Frontend folder and run npm install

For Backend

- go to Backend folder and run npm install

#### Run project

Frontend running on port 3000

- go to frontend folder and run npm start

Backend running on port 3001

- go to backend folder and run mode main.js

## Database Used

- Monogo Atlas : mongoDB(use your username and password for mongo connection in confid/dpConnect.js file)

## Database Models

- User
- UserDashboard
