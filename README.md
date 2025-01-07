# Tech Quiz Test Suite

## Description
This project enhances a fully functioning Tech Quiz application by integrating Cypress for both component and end-to-end tests. 
The app is built using the MERN stack. Users can take a quiz of ten random questions and view their final score.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)
- [Demo](#demo)

## Installation
Clone this repository to your local machine:
git clone https://github.com/itstechagain/Module-19-Challenge

Navigate to the project directory:
cd Module-19-Challenge

Install the required dependencies:
npm install
Reconfigure the required environment variables.

## Usage
Start the server and client:
npm start
Open your browser and navigate to http://localhost:3001 to use the quiz application.
Click the "Start Quiz" button to begin the quiz.
Answer the questions, and once completed, your score will be displayed.
You can choose to start a new quiz after completing the current one.

## Testing
This project uses Cypress for testing. Follow the steps below to run the component and end-to-end tests:

Install Cypress as a dev dependency:
npm install cypress --save-dev
To run the tests, use the following command:
npm run test
Cypress will open its Test Runner. Select the test files to execute:
Component Test: Located in cypress/component/Quiz.cy.jsx
End-to-End Test: Located in cypress/e2e/quiz.cy.js
The tests cover:
Component Test: Ensures the quiz component renders correctly and behaves as expected.
End-to-End Test: Simulates user interaction with the entire quiz application, from starting the quiz to viewing the final score.

## License
![License](This project is not licensed).

## Contributing
No contributions are required at this time.

## Questions
For any questions, please feel free to reach out:
GitHub: itstechagain

## Demo
A walkthrough video: 

