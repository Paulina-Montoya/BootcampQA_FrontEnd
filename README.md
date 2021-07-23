# Bootcamp QA Front-end Framework

## Pre-conditions:
- [Install Node.js](https://nodejs.org/en/download/current/)
- [Install Git](https://git-scm.com/downloads)

## Set up the project:
1. Clone the project:

    `git clone https://github.com/Paulina-Montoya/BootcampQA_FrontEnd`

2. Open the project and run the next command in the terminal to install the libraries from package.json:

    `npm install`

3. In the root folder create a new file with the next name:

    `.env`

4. Open the .env file and add the next variables. In BASE_URL add the home page url, in USER_SUCCESS and a PASSWORD_SUCCESS add a valid email and password to login successfully in the todoist application:

    `BASE_URL=https://baseurl.com/`

    `USER_SUCCESS=validuser@email.com`

    `PASSWORD_SUCCESS=validpassword`

## Run the test cases scripts:
5. Open the terminal and add the next commands to run the test scripts:

    `npm run test-all` : run all the test scripts
   
    `npm run test-login` : run the login test cases
    
    `npm run test-tasks` : run the creation of tasks test cases
    
    `npm run test-suite-smoke` : run the suite smoke

## Create a report:
6. To generate the report run the next command to create the JSON file with the data provided:

    `npm run test-create-report`

7. Run the next command to open the HTML report, it going to open a browser to show the statistics:

    `test-open-report`

## Reviw code:
8. To analyzes the JavaScript code and quickly find problems, run the next command:

    `npm run test-text` 

## Libraries:

- testcafe
- dotenv
- multiple-cucumber-html-reporter
- testcafe-reporter-cucumber-json
- eslint
