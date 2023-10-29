# Test Cases

Below are some Test Case samples that I wrote for PC Garage website.  

-----------------

**Title:**
Creating a new account.

**Description:**
Check if the sign-up works when a person provides the information required (First Name, Last Name, Phone Number, Email, Password).

**Steps to reproduce:**
1. Go to www.pcgarage.ro/autentificare/
2. Complete the First Name, Last Name, Phone Number, Email, Password fields
3. Check the radio button "Sunt de acord cu procesarea datelor personale conform Politicii de Confidentialitate."
4. Click "Creeaza cont" button

**Expected result:**
User should be able to create an account.

**Test data:**
First Name: Vladimir, Last Name: Badea, Phone Number: 0722333444, Email: vladimirtestcase@gmail.com, Password: qwerty.

-----------------

**Title:**
Test login with credentials.

**Description:**
Check if the login works when a person uses a correct email/password.

**Steps to reproduce:**
1. Go to www.pcgarage.ro/autentificare/
2. Add a correct email/password
3. Press "Autentificare" button

**Expected result:**
User should be able to login and is taken to his profile page.

**Test data:**
Email: vladimirtestcase@gmail.com & Password: qwerty.

-----------------

**Title:**
Test login with credentials.

**Description:**
Check if the login works when a person uses an incorrect email/password.

**Steps to reproduce:**
1. Go to www.pcgarage.ro/autentificare/
2. Add an incorrect email/password
3. Press "Autentificare" button

**Expected result:**
User should not be able to login and should be shown either of the following messages "Parola introdusa este gresita. Va rugam sa incercati din nou.", "Adresa de email nu exista in baza noastra de date. Va rugam sa incercati din nou.".

**Test data:**
Email: vladimirtestcase@gmail.com & Password: qwerTY - Correct email and wrong password.
Email: vladimirtestca@gmail.com & Password: qwerty - Incorrect email and correct password.

-----------------

**Title:**
Test the search functionality.

**Description:**
Use the search bar from the www.pcgarage.ro website to search for Macbook Pro 14''.

**Steps to reproduce:**
1. Go to www.pcgarage.ro/cauta/
2. Write the product name
3. Hit "Enter" button on your keyboard

**Expected result:**
User should be able to find the Macbook Pro 14'' in the search results on website.

**Test data:**
For search: Macbook Pro 14''.

-----------------

**Title:**
Test the payment functionality.

**Description:**
Verify if the user can successfully pay for the products he has in the shopping cart using a valid credit card.

**Steps to reproduce:**
1. Go to www.pcgarage.ro
2. Log in to the website
3. Add the desired products to the cart
4. Press the "Trimite comanda" button at the top right corner of your screen
5. Select credit card option for payment
6. Check the following radio button at the bottom of the page: "Am citit si sunt de acord cu conditiile de utilizare si prelucrarea datelor cu caracter personal."
7. Press the "Lanseaza comanda" button at the bottom of the page
8. Provide valid credit card details
9. Select the currency you would like to use for this payment
10. Click on the "Plateste" button at the bottom of the screen

**Expected result:**
User should be able to purchase successfully the desired products using the credit card without any error occuring during payment process.

**Test data:**
* Email: vladimirtestcase@gmail.com & Password: qwerty.
* Cart products: Macbook Pro 14'', Monitor LED 14'', SSD Kingston A400 240GB.
* Credit card details: First Name and Last Name: Vladimir Badea.
* Credit card number: 6547-6644-5544-44XX.
* Payment Type: Visa.
* Expiration Date: 07/2027.
* CVV: 991.
* Currency: RON.
