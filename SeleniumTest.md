## Functional Requirements & Test Cases 

### Login Functionality
1. **Test Case 1:** Verify that the user can log in with valid credentials

    **Given**: the user is on the login page
   **When**: the user enters valid credentials & clicks the login button
   **Then**: the user is successfully logged in

3. **Test Case 2:** Verify that an error message is shown for invalid login

    **Given**: the user is on the login page
   **When**: the user enters invalid credentials and clicks the login button
   **Then**: An error message is be displayed showing an invalid login.

### Search Functionality
1. **Test Case 1** Submitting a Question in the "Contact us" Form

    **Given**: the user is on the “Contact Us” page.
   **When**: the user fills in the required fields and clicks on the “Submit” button.
   **Then**: The form is successfully submitted, and the confirmation message is displayed.
3. **Test Case 2** Submitting with missing required fields

   **Given**: the user is on the “Contact Us” page.
   **When**: the user leaves 1+ required fields empty and tries to submit the form.
   **Then**: an error message is displayed, highlighting the missing information.

### Navigation 
1. **Test Case 1** Verify the access to the navigation menu
 
   **Given**: the user is on the website’s homepage.
   **When**: the user clicks on the navigation menu.
   **Then**: the navigation menu opens,options are displayed. 
2. **Test Case 2** Verifying a non-existent navigation item.
 
   **Given**:the user is on the website’s homepage.
   **When**: the user clicks on a navigation item that doesn’t exist.
   **Then**: error page or no action happens if the page doesn’t exist.
  
## Selenium Commands 
- **verifyText**: Verify that an element contains the expected text, but still doesn't fail the test
- **assertValue**: Assert that an input has the expected value.


