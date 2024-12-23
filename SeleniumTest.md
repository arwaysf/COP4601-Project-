## Functional Requirements & Test Cases 

### Login Functionality
1. **Test Case 1** Verify that a user can log in with valid credentials.
   - Navigate to the login page
   - Enter valid credentials
   - **Expected Result** : successfully logged in
2. **Test Case 2**  Verify that an error message is shown for invalid login
    - Enter invalid credentials
    - Click on the login button.
    - **Expected Result**: Display an error message showing invalid login.

### Search Functionality
1. **Test Case 1** Submitting a Question in the "Contact us" Form
   - Navigate to the “Contact Us” page
   - Fill in the required fields
   - Click the “Submit” button
   - **Expected Result**: The form is successfully submitted, confirmation message appears.
2. **Test Case 2** Submitting with missing required fields
   - Navigate to the “Contact Us” page
   - Leave one or more required fields empty
   - **Expected Result**: An error message appears

### Navigation 
1. **Test Case 1** Verify the access to the navigation menu
   - Click on the navigation menu button.
   - Fill in the required fields
   - Ensure that all menu items are visible.
   - **Expected Result**: The navigation menu opens with all options available 
2. **Test Case 2** Verifying that clicking on a non-existent navigation item results in no action.
   - Click on a navigation item that doesn’t exist
   - Leave one or more required fields empty
   - **Expected Result**: A 404 error page or no action is displayed if the page doesn’t exist.
  
## Selenium Commands 
- **verifyText**: Verify that an element contains the expected text, but still doesn't fail the test
- **assertValue**: Assert that an input has the expected value.


