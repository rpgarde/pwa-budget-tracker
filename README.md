# PWA Budget Tracker
![license](https://img.shields.io/github/license/rpgarde/workout-tracker)

## Description
This is a Progressive Web App budget tracker which allows you to still add entries offline.

See deployed app [here](https://pg-budget-tracker.herokuapp.com/).

<img src="/assets/downloaded-app.PNG" width="40%"> <img src="/assets/mobile-app.PNG" width="40%"> 

## Table of Contents 
* [Technology](#technology)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Questions](#questions)

## Technology 
Starter code was provided for front-end, and I had to build all the backend routes with the following tech:
* Node.js
* Express
* mongoDB
* Mongoose
* PWA

## Installation
If you want to run this locally on your machine:
* Clone / fork to your local machine
* Type npm i on your terminal to install all dependencies
* Type npm run seed to seed the database
* Type npm start to run the application
* Go to http://localhost:3000/ to use the application

## Usage
See deployed app [here](https://pg-budget-tracker.herokuapp.com/)

1. Add an entry by typing the name, amount, and if you're adding / subtracting
2. With each entry, it is added to the chart + the total
3. If you go offline, you can still add / subtract amounts
4. When you go back online, it will sync with the database

## License
This project uses MIT license.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

## Questions
For any further questions, reach out to rpgarde@gmail.com or visit my [Github profile](https://github.com/rpgarde).
