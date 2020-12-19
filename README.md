
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) ![Badge for GitHub repo top language](https://img.shields.io/github/languages/top/hjlogique/Progressive-Budget-Tracker?style=flat&logo=appveyor) ![Badge for GitHub last commit](https://img.shields.io/github/last-commit/hjlogique/Progressive-Budget-Tracker?style=flat&logo=appveyor)
  
# Progressive-Budget-Tracker

  ## Description 
  
  This application allows users to add expenses and deposits to their budget or withdraw from their funds with or without a data/internet connection. When entering transactions offline, once the application is brought back online, database is automatically updated with all information, and the application populates the total amount. This application is also standalone, meaning users can install it on their computers, and use it locally with or without an internet connection.
 
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Questions](#questions)
  * [License](#license)
  
  ## Installation

   To run the application locally go to the project root directory in your terminal and type the `npm i` command to install the NPM package dependencies specified in the `package.json` file. The required modules for this application are [compression](https://www.npmjs.com/package/compression), [express](https://www.npmjs.com/package/express), [lite-server](https://www.npmjs.com/package/lite-server), [mongoose](https://www.npmjs.com/package/mongoose), and [morgan](https://www.npmjs.com/package/morgan).
  
   Next type `npm start` to start the server and run the application.  This application generates a `MongoDB` database called `budget` with a collection called `transactions`. 

  This application is deployed with [Heroku](https://www.heroku.com/home), and [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/signup). You can access it [here](https://stormy-inlet-08148.herokuapp.com/). (It might take a few seconds for the site to load the information)

  
  ## Usage 
  
  No matter users run the application `locally` or access it on `Heroku`, they can `install` it as a `standalone application` to their computers, and it performs exactly the same as the online application running on the server.
 
  Users can create different `transactions` by entering the `Name of transaction` and the `Transaction amount`, and add an amount to their budget or withdraw it from their budget by selecting `Add Funds` or `Subtract Funds` buttons. The total budget is always updated and displayed. All transactions are listed in a table, and all activities over time are displayed in a diagram.  

  Using the online version of the app or installing the standalone one, users can go offline and apply some changes to their budgets. Once they reconnect to the internet, all the changes they made are stored in the database. (See the screenshots below).
  
  ![image 1](/screenshots/img1.png)

  ![image 2](/screenshots/img2.png)

  
  ## Questions
  
  [Link to my GitHub profile](https://github.com/hjlogique)

  If you have any questions, please contact me via email:
  
  Email: hjlogique@yahoo.com
  
  ## License
  
  MIT License