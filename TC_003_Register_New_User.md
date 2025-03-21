#  Test Case ID: TC_003_Register_New_User

**Title:** Register

**Tested Page:** https://demo.opencart.com/

**Priority:** High
**Test Type:** Manual 
**Precondition:** User is on the homepage of the OpenCart demo site  
**Tested By:** Hakicu
**Date:** 24/11/2024

---

## Description:
Verify that a new user can successfully register an account on the OpenCart Demo site.

---

## Test Steps:

| Step | Action |
|------|--------|
| 1 | Go to https://demo.opencart.com/ |
| 2 | Click on the "My Account" link in the top-right corner of the homepage. |
| 3 | Click on the "Register" link from the dropdown menu. |
| 4 | Fill out the registration form with valid details (First Name, Last Name, Email, Password, etc.). |
| 5 | Agree to the Terms & Conditions and click the "Continue" button. |
| 6 | Verify the success message and check your email for the confirmation email. |
| 7 | Navigate to the homepage and check if the user is logged in. |
---

## Expected Result:
- The **OpenCart Demo** site should load without issues.
- The **"My Account"** dropdown menu should appear and display the "Register" option.
- The **registration form** should accept the input without errors.
- After submitting the form, a **success message** should appear, and a **confirmation email** should be sent.
- The user should be **automatically logged in**, and the homepage should reflect the login.


---

## Postcondition:
- The user should be successfully registered and logged in.
- A confirmation email should be sent, and the user should have access to their account.
- User session should remain active until they log out or close the browser.

---

## Notes:
- Ensure that the email used for registration is valid.
- Take note of the time taken for the confirmation email to arrive.
- Perform the test with invalid registration details to check error handling.
