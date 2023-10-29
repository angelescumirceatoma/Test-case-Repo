# TestCases

Below are Test cases for checking several important functionalities of the iStyle website. 


-----------------

**Title: Creating a new account**

**Description:**
Check if the sign-up works when a person provides the necessary name, surname, email, and password.

**Steps to reproduce:**
1. Go to https://istyle.ro/customer/account/login/referer/aHR0cHM6Ly9pc3R5bGUucm8v/
2. Click the 'Nu ai cont? Click aici' button
3. Complete the name, surname, email and password fields
4. Click the radio button: 'Am citit și sunt de acord cu Termenii si conditiile, cu Politica de confidentialitate'
5. Click on 'Nu ai cont? Click aici' button

**Expected result:**
The user should be able to create an account and be taken to his profile page.

**Test data:**
Name: Mircea & Surname: Angelescu & Email: mirceatoma@email.com & Pass: abcdefgh2023!


-----------------

**Title: Logging in into account**

**Description:**
Check if the login works when a person uses the correct email/pass.

**Steps to reproduce:**
1. Go to https://istyle.ro/customer/account/login/referer/aHR0cHM6Ly9pc3R5bGUucm8v/
2. Add a correct email/pass
3. Press 'Autentificare' button

**Expected result:**
The user should be able to log in and be taken to his profile page.

**Test data:**
Email: mirceatoma@email.com & Pass: abcdefgh2023!

-----------------


**Title: Login with invalid credentials**

**Description:**
Check if the login works when a person uses the wrong email/pass combination.

**Steps to reproduce:**
1. Go to https://istyle.ro/customer/account/login/referer/aHR0cHM6Ly9pc3R5bGUucm8v/
2. Add an invalid email/pass
3. Press 'Autentificare' button

**Expected result:**
The user should not be able to log in and throw an error on the current page telling user the email or the password is incorrect. 

**Test data:**
Email: mirceqtomi@emil.com & Pass: abgSaw2033!.


-----------------
**Title: Test the search functionality**

**Description:**
Use the search bar from the www.istyle.ro website to search for iPhone 14 Pro.

**Steps to reproduce:**
1. Go to https://www.istyle.ro/
2. Write the product name 'iPhone 14 Pro'
3. Hit 'Enter' on your Keyboard

**Expected result:**
User should be able to find iPhone 14 Pro in the search results. 

**Test data:**
For searches: iPhone 14 Pro.


-----------------
**Title: Test the payment functionality**

**Description:**
Verify if the user can successfully pay for the products using a valid credit card.

**Steps to reproduce:**
1. Go to https://www.istyle.ro/
2. Log in to the site
3. Add 'iPhone 15 Pro' to the cart
4. Press the 'Finalizare comanda' button
5. Press the 'Continua catre datele de livrare' button
6. Complete Name, Surname, County, City, Adress, and Phone Number
7. Press the 'Continua catre sectiunea de plata' button
8. Choose the credit card payment option from the dropdown
9. Enter your valid card details using PayU
10. Press the 'Plateste' button

**Expected result:**
User should be able to purchase successfully the products using the credit card without any error.

**Test data:**
* Email: mirceatoma@email.com & Pass: abcdefgh2023!
* Cart products: iPhone 15 Pro
* Credit card details: First and Last Name: Mircea Angelescu
* Credit card number:8815-4321-4946-99XX
* Payment Type: Visa
* Expiration Date: 09/2027
* CVV:021

-----------------
