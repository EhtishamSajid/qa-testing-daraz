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

## TC-11: Verify product details page loads correctly

**Related Scenario:** TS-11  

**Precondition:** User is on product listing page  

**Steps:**
1. Click on any product  
2. Wait for product details page to load  

**Expected Result:**  
Product details page should load successfully without errors  

**Actual Result:**  
Product details page loaded successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-12: Verify product images are displayed properly

**Related Scenario:** TS-12  

**Precondition:** User is on product details page  

**Steps:**
1. Open any product page  
2. Observe product images  

**Expected Result:**  
All product images should load clearly without distortion or missing thumbnails  

**Actual Result:**  
Product images displayed correctly and clearly  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-13: Verify product price and description are visible

**Related Scenario:** TS-13  

**Precondition:** User is on product details page  

**Steps:**
1. Open any product page  
2. Observe product price and description section  

**Expected Result:**  
Product price and description should be visible and readable  

**Actual Result:**  
Product price and description were visible successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-14: Verify user can add product to cart

**Related Scenario:** TS-14  

**Precondition:** User is on product details page  

**Steps:**
1. Select any product  
2. Click “Add to Cart” button  

**Expected Result:**  
Selected product should be added to cart successfully  

**Actual Result:**  
Product added to cart successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-15: Verify user can remove product from cart

**Related Scenario:** TS-15  

**Precondition:** Product already exists in cart  

**Steps:**
1. Open cart  
2. Click remove/delete button on product  

**Expected Result:**  
Product should be removed from cart successfully  

**Actual Result:**  
Product removed from cart successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-16: Verify quantity update in cart

**Related Scenario:** TS-16  

**Precondition:** Product exists in cart  

**Steps:**
1. Open cart  
2. Increase or decrease product quantity  

**Expected Result:**  
Cart quantity and total price should update correctly  

**Actual Result:**  
Quantity updated but total price did not update immediately  

**Status:**  
Fail

----------------------------------------------------------------------------------------------------------------------

## TC-17: Verify cart retains items after page refresh

**Related Scenario:** TS-17  

**Precondition:** Product exists in cart  

**Steps:**
1. Add product to cart  
2. Refresh browser page  

**Expected Result:**  
Cart items should remain saved after refresh  

**Actual Result:**  
Cart items remained available after refresh  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-18: Verify user can proceed to checkout

**Related Scenario:** TS-18  

**Precondition:** Product exists in cart  

**Steps:**
1. Open cart  
2. Click checkout button  

**Expected Result:**  
User should be redirected to checkout page  

**Actual Result:**  
User redirected to checkout page successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-19: Verify address selection during checkout

**Related Scenario:** TS-19  

**Precondition:** User is on checkout page  

**Steps:**
1. Select delivery address  
2. Save/confirm address  

**Expected Result:**  
Selected address should be saved successfully  

**Actual Result:**  
Address saved successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-20: Verify order summary is displayed correctly

**Related Scenario:** TS-20  

**Precondition:** User is on checkout page  

**Steps:**
1. Proceed to order summary section  
2. Observe product details and pricing  

**Expected Result:**  
Order summary should display correct products, quantity, and pricing  

**Actual Result:**  
Order summary displayed correct information successfully  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-21: Verify homepage loads without errors

**Related Scenario:** TS-21  

**Steps:**
1. Open Daraz homepage  

**Expected Result:**  
Homepage should load successfully without broken UI or loading issues  

**Actual Result:**  
Homepage loaded successfully without errors  

**Status:**  
Pass

----------------------------------------------------------------------------------------------------------------------

## TC-22: Verify all links are clickable and working

**Related Scenario:** TS-22  

**Steps:**
1. Click multiple navigation and footer links  

**Expected Result:**  
All links should redirect to correct pages successfully  

**Actual Result:**  
Some footer links redirected to incorrect pages  

**Status:**  
Fail

----------------------------------------------------------------------------------------------------------------------

## TC-23: Verify responsiveness on different screen sizes

**Related Scenario:** TS-23  

**Steps:**
1. Resize browser window  
2. Test website on mobile/tablet view  

**Expected Result:**  
Website layout should adjust properly on all screen sizes  

**Actual Result:**  
Navbar overlapped on smaller screen sizes  

**Status:**  
Fail

----------------------------------------------------------------------------------------------------------------------

## TC-24: Verify error messages are user-friendly

**Related Scenario:** TS-24  

**Steps:**
1. Trigger validation or error messages  
2. Observe displayed message  

**Expected Result:**  
Error messages should be clear, meaningful, and easy to understand  

**Actual Result:**  
Error messages were understandable and user-friendly  

**Status:**  
Pass
