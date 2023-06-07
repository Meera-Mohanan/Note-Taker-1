# Note-Taker
  ![MIT license](https://img.shields.io/badge/license-MIT-blue)

## Description  
Note Taker can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file. 

## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation
    1.Install NODE.js to run this application
    2.Create a .gitignore file and include node_modules/ and .DS_Store/ so that your node_modules directory isn't tracked or uploaded to GitHub. Be sure to create your .gitignore file before installing any npm dependencies.
    3.Make sure that your repo includes a package.json with the required dependencies. You can create one by running npm init when you first set up the project, before installing any dependencies.
    4.Run command npm i inquirer@8.2.4 from the integrated terminal to install inquirer.js package dependency.
    5.Run command npm npm i express to install express package.
    6.Run command npm i uuid to install uuid package to generate unique id.
    7.The application will be invoked by using the following command: node server.js.This will start localhost server on PORT 3001.
    8.Open browser and type http://localhost:3001/ to run this application on your local machine.

  ## Usage
    1.When opening the deployed Note Taker application, the user is presented with a landing page with links to a note page. 
    2.When clicked on get started button, user is presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note's text in the right-hand column.
    3.When the user enters a new note title and text, then a Save icon appears in the navigation bar at the top of the page.
    4.When the user clicks on the Save icon, then the new note is saved and appears in the left-hand column with the other existing notes.
    5.When an existing note in the list in the left-hand column is clicked, then that note appears in the right-hand column.
    6.When clicked on the delete button in the list of the left-hand column next to the saved note, then the note gets deleted or diappears.
    7.When the user clicks the Write icon in the navigation bar at the top of the page, then they are presented with empty field to enter a new note title and text in the right-hand column.


  ## License
  
    This project is licensed under the MIT
.

  ## Contributing
  
    Email me if you wish to contribute

  ## Tests
     To run test, run the following command:
  ```
  npm test
  ```
  ## Screenshot


  ## Questions
 
    If you have any questions about the repo, please open an issue or contact me directly at meera.mohanan@gmail.com. you can find more of my work at [Meera-Mohanan](https://github.com/Meera-Mohanan)

## Link to deployed application