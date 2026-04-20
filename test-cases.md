# Test Cases – Authentication

# TC-01: Login with valid credentials

**Related Scenario:** TS-01  

**Precondition:** User must be registered  

**Steps:**
1. Navigate to login page  
2. Enter valid registered email  
3. Enter correct password  
4. Click login  

**Expected Result:**  
User should be successfully logged in and redirected to homepage/dashboard  

**Actual Result:**  
User was successfully logged in and redirected to homepage/dashboard  

**Status:**  
Pass

-----------------------------------------------------------------------------------------------------------

# TC-02: Login with invalid credentials

**Related Scenario:** TS-02  

**Precondition:** User is on login page  

**Steps:**
1. Enter invalid email or password  
2. Click on login button  

**Expected Result:**  
System should display an error message like “Invalid email or password”  

**Actual Result:**  
Invalid email or password 

**Status:**  
Pass

-----------------------------------------------------------------------------------------------------------

# TC-03: Login with empty fields

**Related Scenario:** TS-03  

**Precondition:** User is on login page  

**Steps:**
1. Leave email and password fields empty  
2. Click on login button  

**Expected Result:**  
System should show validation messages like “This field is required”  

**Actual Result:**  
This field is required, fill it.

**Status:**  
Pass

-----------------------------------------------------------------------------------------------------------------

# TC-04: Verify password masking

**Related Scenario:** TS-04  

**Precondition:** User is on login page  

**Steps:**
1. Enter password in password field  

**Expected Result:**  
Password should be hidden (shown as dots or asterisks)  

**Actual Result:**  
Password isn't visible & is hidden i.e: ******

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

# TC-05: Logout functionality

**Related Scenario:** TS-05  

**Precondition:** User must be logged in  

**Steps:**
1. Click on profile/account menu  
2. Click on logout option  

**Expected Result:**  
User should be logged out and redirected to login/home page  

**Actual Result:**  
Logout successfully, redirected to login page.

**Status:**  
Pass
