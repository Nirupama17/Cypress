# Cypress

Followed the below steps:

1. Installed Node.js and NPM.
2. Created a new folder for Cypress project.
3. Opened the terminal and navigated to project directory. Initialized a new Node.js project by running the command: npm init.
4. Installed Cypress by running the command: npm install cypress --save-dev.
5. Opened cypress by running the command: node_modules/.bin/cypress open. (Opened Test runner)
6. In the Test Runner, created a new test file by clicking on the "New File" button and created new file ".spec.js" extension.
7. Added 'specPattern' in cypress.config.js
7. Inside the test file, used the 'describe' function to group related tests and the 'it' functions to define individual test cases.
	- Created 3 tests under describe which contains one 'beforeEach()'
	1. Displayed seven popular products.
	2. Search and verify correct result for product.
	3. Informs the user that there is 1 item in their cart.
8. Tried to run file using both ways (Command line and Testrunner)
