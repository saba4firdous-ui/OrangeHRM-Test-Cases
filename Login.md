## Test Case ID: TC_LOGIN_001

**Test Case Title**: Verify login with valid username and valid password

**Module**: Login

**Priority**: High

**Preconditions**:

-OrangeHRM demo application is accessible.  
-Valid OrangeHRM demo credentials are available.  
-User account is active.  

**Test Data**:

-Username: Admin  
-Password: admin123  

**Test Steps**:

1. Open the OrangeHRM demo login page.  
2. Verify that the Login page is displayed.  
3. Enter Admin in the Username field.  
4. Enter admin123 in the Password field.  
5. Click the Login button.  

**Expected Result**:

* User should be successfully authenticated.  
* User should be redirected to the Dashboard.  
* Dashboard should be displayed without any login error message.

**Status**: Pass 
