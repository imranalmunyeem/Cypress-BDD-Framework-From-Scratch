# Cypress-BDD-Framework-From-Scratch (N.B: This file will keep getting updated)

## Project Setup
           ---> Install npm and nodejs
           
           ---> Creare a folder, open it in VSCode, open the termninal. 
           
           ---> Run "npm init" and set up the package.json
           
           ---> Run "npm install cypress" to install cypress
                
           ---> Run "npx cypress open" to get the test format, plugins, and other necessary things.
           
           ---> Run "npm install --save-dev cypress-cucumber-preprocessor" to install Cucumber.
           
           ---> Add this to "cypress/plugins/index.js"
                      "const cucumber = require('cypress-cucumber-preprocessor').default
                      module.exports = (on, config) => {
                      on('file:preprocessor', cucumber())
                      }

### Help + Testing
The steps below will show how you can run and test this project.


### Report Making Guide



### Running from Jenkins


 
