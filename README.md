# cypressTest
cypress e2e test for to do web app

What is cypress

Cypress is a next generation front end testing tool built for the modern web. We address the key pain points developers and QA engineers face when testing modern applications.

How to Start

1. Clone the project https://github.com/SuthanR/cypressTest.git
2. npm i - Install all the dependencies
3. Run "npx cypress open" in your directory to execute the tests in Test Runner 
4. Run "npx cypress run" to execute the tests in CLI headless | Run "npx cypress run --browser chrome" to execute in browser

Folder and config:

Conf.js: The files defines in integration folder will pick for execution based the cypress.json config.As I used cucumber BDD sytle, the config is define in plugin index.js

The folder(cucumberTest) in integration folder contains the feature files that will be executed as part of test and the step defination or .js files has the cypress commands to execute.

How to generate report

1.npm i --D mocha mochawesome mochawesome-merge mochawesome-report-generator
2.Add the config in cypress.json
3.Add the scripts in package.json
4.npx cypress run
5.npm run create:html:report

Documentation refered:

Commands: https://docs.cypress.io/api/table-of-contents

Plugins: https://docs.cypress.io/plugins/directory


