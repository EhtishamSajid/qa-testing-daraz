# Bug Reports – Daraz.pk

This document contains bugs identified during manual testing of Daraz.pk.

-------------------------------------------------------------------------------------------------------

## BUG-01: Search displays unrelated products for invalid keywords

**Related Test Case:** TC-07  
**Module:** Search  
**Severity:** Medium  
**Priority:** Medium  

### Steps to Reproduce
1. Open Daraz homepage  
2. Enter random text in search bar (e.g. xyzabc123)  
3. Click on search button  

### Expected Result
System should display message: “No products found”

### Actual Result
System displayed unrelated/random products instead of showing “No products found” message

### Status
Open

<img width="1919" height="909" alt="image" src="https://github.com/user-attachments/assets/90cdf140-f091-4a83-8c5f-ce3523bd12e2" />


-------------------------------------------------------------------------------------------------------

## BUG-02: Cart total price does not update immediately after quantity change

**Related Test Case:** TC-16  
**Module:** Cart  
**Severity:** High  
**Priority:** High  

### Steps to Reproduce
1. Add any product to cart  
2. Increase or decrease product quantity  
3. Observe total price section  

### Expected Result
Total price should update immediately according to selected quantity

### Actual Result
Quantity updated successfully but total price remained unchanged until page refresh

### Status
Open

-------------------------------------------------------------------------------------------------------

## BUG-03: Some footer links redirect to incorrect pages

**Related Test Case:** TC-22  
**Module:** Navigation/Footer  
**Severity:** Medium  
**Priority:** Medium  

### Steps to Reproduce
1. Scroll to footer section  
2. Click multiple footer links  

### Expected Result
Each link should redirect to its correct corresponding page

### Actual Result
Some links redirected to unrelated or incorrect pages

### Status
Open

-------------------------------------------------------------------------------------------------------

## BUG-04: Navbar overlaps content on smaller screen sizes

**Related Test Case:** TC-23  
**Module:** UI/Responsiveness  
**Severity:** Medium  
**Priority:** High  

### Steps to Reproduce
1. Open website on mobile view or resize browser window  
2. Observe navbar layout  

### Expected Result
Navbar should adjust properly without overlapping page content

### Actual Result
Navbar overlapped page content on smaller screen sizes

### Status
Open

