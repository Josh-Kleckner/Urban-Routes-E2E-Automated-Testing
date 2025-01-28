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

## How to Run the Tests
1. Clone the repository to your local system:  
   ```bash
git clone <repository-url>
2. Navigate to the project directory:
   ```bash
cd ./hm08-qa-us
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
