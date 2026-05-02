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

----------------------------------------------------------------------------------------------------------------------

# Test Cases – Search & Navigation

## TC-06: Search with valid product name

**Related Scenario:** TS-06  

**Precondition:** User is on homepage/search bar is visible  

**Steps:**
1. Enter a valid product name in search bar  
2. Click on search button or press Enter  

**Expected Result:**  
Relevant products related to the searched keyword should be displayed  

**Actual Result:**  
Relevant products were displayed successfully based on the searched keyword  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-07: Search with invalid/random text

**Related Scenario:** TS-07  

**Precondition:** User is on homepage/search bar is visible  

**Steps:**
1. Enter random/non-existing product text in search bar  
2. Click search button  

**Expected Result:**  
System should display message like “No products found”  

**Actual Result:**  
System displayed unrelated/random products instead of “No products found” message  

**Status:**  
Fail

----------------------------------------------------------------------------------------------------------------------

## TC-08: Verify search suggestions appear while typing

**Related Scenario:** TS-08  

**Precondition:** User is on homepage/search bar is visible  

**Steps:**
1. Click on search bar  
2. Start typing product name slowly  

**Expected Result:**  
Search suggestions should appear dynamically while typing  

**Actual Result:**  
Relevant search suggestions appeared while typing  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-09: Verify user can navigate through categories

**Related Scenario:** TS-09  

**Precondition:** User is on homepage  

**Steps:**
1. Click on any product category  
2. Navigate to subcategories/products  

**Expected Result:**  
User should be redirected to selected category page successfully  

**Actual Result:**  
Selected category page opened successfully with related products  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-10: Verify filters (price/category) work correctly

**Related Scenario:** TS-10  

**Precondition:** User has searched for a product  

**Steps:**
1. Apply price filter  
2. Apply category filter  
3. Observe filtered results  

**Expected Result:**  
Products should be displayed according to selected filters  

**Actual Result:**  
Products were filtered correctly according to selected filters  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-10: Verify filters (price/category) work correctly

