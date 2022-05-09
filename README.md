# Cypress-BDD-Framework-From-Scratch (N.B: This file will keep getting updated)

## Project Setup
           ---> Install npm and nodejs
           
           ---> Creare a folder, open it in VSCode, open the termninal. 
           
           ---> Run below command to initialize npm package
                      npm init
           
           ---> Run below command to install cypress
                      npm install cypress
                
           ---> Run below command to get the test format, plugins, and other necessary things.
                      npx cypress open
           
           ---> Run below command to install Cucumber.
                      npm install --save-dev cypress-cucumber-preprocessor
           
           ---> Add the below commands to "cypress/plugins/index.js"
                      const cucumber = require('cypress-cucumber-preprocessor').default
                      module.exports = (on, config) => {
                      on('file:preprocessor', cucumber())
                      }
           
           ---> Add support below commands to "cypress.json" for feature files to your Cypress configuration
                      {
                       "testFiles": "**/*.feature"
                      }
                     
           ---> Add below commands to "package.json" to create a configuration for the plugin
                     "cypress-cucumber-preprocessor": {
                       "nonGlobalStepDefinitions": true
                      }         

### Help + Testing
The steps below will show how you can run and test this project.


### Report Making Guide



### Running from Jenkins


 
