
**Test Case ID**: TC_LOGIN_002

**Test Case Title:** Verify login with valid username and invalid password

**Module:** Login

**Priority:** High

**Preconditions**

- OrangeHRM demo application is accessible.
- Valid OrangeHRM username is available.
- User is on the OrangeHRM Login page.

**Test Data**

- Username: `Admin`
- Password: `admin124`

**Test Steps**

1. Open the OrangeHRM demo login page.
2. Verify that the Login page is displayed.
3. Enter `Admin` in the Username field.
4. Enter `admin124` in the Password field.
5. Click the **Login** button.

**Expected Result**

The system should reject the login attempt and display the error message **"Invalid credentials"**.

**Actual Result**

The system rejected the login attempt and displayed the error message **"Invalid credentials"**.

**Test Status**

**PASS**

**Test Evidence**

Screenshot attached.
