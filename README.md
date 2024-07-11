This project contains a Cypress test to automate the submission of a Health Survey Form.

# Prerequisites

- Node.js and npm (or yarn) installed on your system.
- Basic understanding of JavaScript and web development.
- Familiarity with Cypress is helpful.

# Installation and Creating Test File

- Create a folder and go to the path and type 'cmd' to open the command prompt.
- In the Command prompt, run the following command to install Cypress:
    => npm install cypress --save-dev
- Run the following command to open cypress test runner:
    => npx cypress open
- After opening the cypress, click on E2E Testing > continue > select a browser and click on 'Start E2E Testing'.
- After opening the browser, click on 'Create New Spec' that will create a test file -> "HealthSurvey.cy.js".
- open the Visual Studio code, click on File > Open Folder > select the folder that you created.
- In the e2e folder you can find the test file -> "HealthSurvey.cy.js" you created.
- Write the test to automate.

# Test Description

- Navigate to the form: Opens the provided Google Form URL.
- Enter your name: Fills in the "Your Name" field with "John Doe".
- Select your age: Chooses the appropriate age group.
- Select "Yes or No" from the "Do you exercise every week?" dropdown: Answers the exercise frequency question.
- Submit the form: Clicks the submit button.
- Verify form submission: Checks for a confirmation message indicating successful submission.

# Run the test

- Run one of the following command in VS code terminal to open cypress test runner:
    => npx cypress open
        (or)
    => npx cypress run --browser edge --spec "cypress\e2e\HealthSurvey.cy.js"

- It will start automating the test.