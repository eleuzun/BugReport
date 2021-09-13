# Bug Report

Below are some Bug Report samples that I wrote while working on previous projects.

## Login is not working properly

**Priority & Severity** 
P2-High

**Description:**
When trying to login with the correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Steps to Reproduce**
1. Go to www.website.com/login
2. Add a correct user/pass

**Expected Result:**
User should be able to login and is taken to his profile page.

**Actual Result:**
User is not logged and no error appears.

**Test Data User:**
radu & Pass: 123456

## Cart does not display the items number

**Priority & Severity**
P2-High

**Description:** 
When trying to login with the correct credentials, nothing happens. The user is not logged in and no error message is displayed.

**Steps to Reproduce**
1. Go to www.website.com/login
2. Add a correct user/pass

**Expected Result:**
User should be able to login and is taken to his profile page.

**Actual Result:**
User is not logged and no error appears.

**Test Data User:**
radu & Pass: 123456

## Purchase functionality is not working properly 

**Priority and Severity**
P2 - High

**Description:**
When pressing the purchase button it endlessly displays the Thank you for your purchase message and an id number for the order. When pressing again the purchase button it changes the id number for the same order.

**Steps to Reproduce**
1. Go to www.demoblaze.com
2. Press on Samsung galaxy s6
3. Click Add to cart 
4. Click Ok button
5. Click on Cart
6. Press the Place Order button
7. Fill in the required fields 
8. Press the Purchase button
9. Press again on Purchase button (don’t press OK)

**Expected Result:**
The buyer should be allowed to press only one time the Purchase button and should be able to receive once a Thank you for your order message an ID number for  his order and an email with the purchase details (AWB, invoice, a tracking number and a tracking link) . 

**Actual Result:**
The buyer is allowed to press the Purchase button endlessly and receives a Thank you for your order message with different ID numbers without an email and order details.

**Test Data:**

Place Order details : Name : Elena, Country : Romania, City: Brașov, Credit card: 123456789, Month: 14, Year :2025

## Changing the quantity of an item in the cart is not possible

**Priority and Severity**
P4-Medium

**Description:**
The user should be able to change the quantity of an item in the cart by clicking on the quantity field.

**Steps to Reproduce**
1. Go to www.demoblaze.com
2. Press on Samsung galaxy s6
3. Add to cart
4. Press the OK button
5. Click on Cart

**Expected Result:**
The user should be allowed to change the quantity of an item in the cart.

**Actual Result:**
The shopping cart doesn’t have a quantity field and the user can’t update the quantity of an item. 

![STORE](https://user-images.githubusercontent.com/87574407/133063509-8d3dd0cd-2224-466e-a168-fd9dc503b67a.png)

## Customer Login does not have a password option

**Priority and Severity**
P1- Critical

**Description:**
The user should be able to access his account using his credentials username and pass.

**Steps to Reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login
2. Click Customer Login
3. Click  --Your Name-- field
4. Select a user
5. Click the Login button

**Expected Result:**
The user should be able to access his profile by inserting his name and password. 

**Actual Result:**
The user can access his profile using only his user without using a password.

**Test Data** 
User:Elena Uzun

