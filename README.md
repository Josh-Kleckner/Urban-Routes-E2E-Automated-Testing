Josh Kleckner
# Urban Routes End-to-End Automated Testing

## Description
This project focuses on testing the core functionality of the UrbanRoutes app by developing and executing automated tests using WebDriverIO and Mocha. It highlights the use of modern testing tools and techniques to ensure the app delivers a smooth and reliable user experience.

## Key Technologies
- **Git Bash** for version control  
- **VS Code** as the development environment  
- **WebDriverIO** and **Mocha** for test automation  
- **Node.js** for dependency and test management  

## Techniques Used
- **Page Object Model** for organized and reusable selectors  
- **Network Request Interceptor** to monitor and modify API calls  
- **Element visibility tests** using `.waitForDisplayed()`  
- **Dynamic data generation** for creating randomized phone numbers  
- **Modular structure** with exports and imports for cleaner code organization  
- **Interactive element handling** for clicks, inputs, and browser pauses

## Tasks
Write several tests to check the functionality of Urban Routes. Write your tests in the createAnOrder.e2e.js file located in the test/specs folder.
   <details>
     <summary>Expand Task Details</summary>
     Write automated tests covering the full process of ordering a taxi. The tests should cover:

   1. Setting the address
   2. Selecting Supportive plan
   3. Filling in the phone number
   4. Adding a credit card (Tip: the “link” button doesn’t become active until the card CVV field on the “Adding a card” modal id=”code” class=”card-input” loses focus. To change focus you can simulate the user pressing TAB or clicking somewhere else on the screen).
   5. Writing a message for the driver
   6. Ordering a Blanket and handkerchiefs (Tip: there are two selectors to be aware of here. One selector to click on and one to run expect on to verify that the state changed).
   7. Ordering 2 Ice creams
   8. The car search modal appears
   9. Waiting for the driver info to appear in the modal (optional) In addition to the steps above there is an optional step you can check. This one is a bit more tricky than the others but it’s good practice since you will likely encounter more difficult tasks in your career.

The driver search modal will appear and there will be a countdown while a driver is assigned. The modal will change from showing the car search to the drive info, as shown below:
![Driver Search Modal](https://practicum-content.s3.amazonaws.com/resources/Screenshot_2023-04-29_at_11.31.02_AM_1685550689.png)
</details>

## How to Run the Tests
1. Clone the repository to your local system:  
   ```bash
   git clone <repository-url>
2. Navigate to the project directory:
   ```bash
   cd ./urbanRoutesAutomatedTesting
3. Install the required dependencies:
   ```bash
   npm install webdriverio --save-dev  
   npm install mocha --save-dev  
4. Replace the baseURL in the wdio.config.js file with a current server URL from TripleTen.
5. Run the test suite:
   ```bash
   npm run wdio

## Conclusion
This project demonstrates my expertise in writing robust functional tests, implementing advanced testing techniques like intercepting network requests and using dynamic data, and ensuring code modularity for maintainability. It underscores my ability to identify and test critical application workflows while leveraging best practices in test automation.
