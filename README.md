# Bug Report

Below are some Bug Report samples that I wrote while working on previous projects.

## Login is not working properly

**Priority & Severity:** 
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

**Priority & Severity:**
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

**Priority and Severity:**
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

**Priority and Severity:**
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

**Priority and Severity:**
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

**Test Data:** 
User:Elena Uzun

## Broken link on the homepage

**Priority and Severity:** 
P5 Low

**Description:**
When the user is trying to acces the link  the page can not be displayed.

**Steps to Reproduce**
1. Go to https://www.primariatechirghiol.ro/
2. Go to Info Turism
3. Press the Cazare option
4. Press Villa Bella

**Expected Result:**
When pressing  Villa Bella, the user is redirected to a web page where he can find the desired info about the accommodation. 

**Actual Result:**
When pressing Villa Bella, the user is redirected to a  web page where “The site can't be reached info is displayed.”

## Custom 404 Error page is not created

**Priority and Severity:**
P4 Low

**Description:**
When accessing the web page with an incorrect or misspelled word a 404 Error Page is not created.

**Steps to Reproduce**
1. Go to www.primariatechirghiol.ro
2. Insert a misspelled word in the URL - “jjjjjjjiiiii”
3. Click Enter 

**Expected Result:**
When accessing the web page with an incorrect or misspelled word a Custom 404 Error Page should provide helpful content that encourages users to explore the site further.

**Actual Result:**
When accessing the web page with an incorrect or misspelled word a Custom 404 Error Page is not created. An “Error 404 - Not Found” message is displayed on the page.

## No letters should be allowed inside the fields  

**Priority and Severity:**
P4 Normal

**Description:**
The user should be able to insert only numbers in the required fields. 

**Steps to Reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Type in numbers inside the required fields 

**Expected Result:**
The user should be able to insert only numbers in the required fields. 

**Actual Result:**
The user can insert numbers and the letter "e" inside the required fields.

## Failed to load picture 

**Priority and Severity:** 
P5 Low

**Description:**
After accessing the app, the user should visualize a "No smoking" picture on the left side of the screen.

**Steps to Reproduce**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/

**Expected Result:**
On the left side of the screen there should be a "No smoking" picture. 

**Actual Result:**
The "No smoking" picture is not displayed on the left side of the screen.

![600px-No_smoking](https://user-images.githubusercontent.com/87574407/133067961-a68926cc-5c23-48f9-9d11-6aa39cb22eae.png)

## The price does not use  currency symbol

**Priority & Severity:**
P3 High

**Description:**
The price should be indicated with a currency symbol.

**Steps to Reproduce:**
1. Go to https://juice-shop.herokuapp.com/#/

**Expected Result:**
Each product should have a price-tag indicated with a currency symbol.

**Actual Result:**
The price does not have a currency symbol.

## Login error

**Priority & Severity:**
P1 Critical

**Description:**
When trying to login an error message appears.

**Steps to Reproduce**
1. Go to https://juice-shop.herokuapp.com/#/
2. Click Account 
3. Click Login 
4, Use the correct credentials
5. Click Log in button

**Expected Result:**
The user should be able to login and acces his profile page.

**Actual Result:**
The user can not login and an error message appears. 

**Test Data:**
Email: uzun_elena@yahoo.com
Pass : eleuzun
![login Juice Shop](https://user-images.githubusercontent.com/87574407/133068968-97a61c23-196b-4f5d-bd83-7eb2b8925681.png)


## Forgot Password is not allowing user to reset his password

**Priority & Severity:**
P3 High

**Description:**
The user should be able to reset his password by filling the required fields,

**Steps to Reproduce**
1. Go to https://juice-shop.herokuapp.com/#/
2. Click Account button
3. Click Login button
4. Click on Forgot your password?
5. Fill in the required fields 

**Expected Result:**
The user should be able to insert the required information in each section.

**Actual Result:**
The user can fill in the required information only in the Email section. The user can not acces other sections.

![forgot pass Juice Shop](https://user-images.githubusercontent.com/87574407/133068649-7b47138d-5447-4f8c-8ecf-00a486ecd2d4.png)

## Value ''Clouds'' can not be translated 

**Priority and Severity:**
P4 Normal

**Description:** 
When changing the language in the API, the value ''Clouds'' can not be translated in the required language.

**Steps to Reproduce**
1. Go to https://identity.getpostman.com/login
2. Sign in with the correct credentials
3. Click on Workspaces
4. Click on My Workspace 
5. Click on Weather 
6. Click on Get weather by city name
7.  Change the value of lang 
8. Check the response 

**Expected Result:**
The value ''Clouds'' is  translated in the required language.

**Actual Result:** 
The value ''Clouds'' is not translated in the required language.

**Test Data:**
Email or Username: uzun_elena@yahoo.com
Pass: Brasov2014

## A non-existing user ID can be deleted

**Priority and Severity:**
P5 Low

**Description:**
When trying to delete a non-existing user ID an error message should appear on the screen.

**Steps to Reproduce**
1. Go to https://identity.getpostman.com/login
2. Sign in with the correct credentials
3. Click on Workspaces
4. Click on My Workspace 
5. Click on Teste CRUD
6. Click on Delete 

**Expected Result:**
When inserting a non-existing user ID and click on Send button, an error message should appear on the screen.

**Actual Result:** 
When inserting a non-existing user ID and click on Send button, a ''[{"success":"1"}]'' appears on the screen.

**Test Data:**
Email or Username: uzun_elena@yahoo.com
Pass: Brasov2014

![unexisting user](https://user-images.githubusercontent.com/87574407/133069826-7f71d371-4746-4a0f-8ef5-4d3cffe95a51.png)

