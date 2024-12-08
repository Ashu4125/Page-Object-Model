# Automation Testing with Selenium and TestNG

This project is an automation testing solution for the login functionality and shopping flow of the website [Practice Automation Testing](https://practice.automationtesting.in/my-account/). The tests are automated using **Selenium WebDriver** and **TestNG**.

## Test Case Overview

### 1. **Login Functionality**
   - Navigate to the login page.
   - Enter valid credentials (username and password).
   - Verify successful login by checking if the user is redirected to the homepage.

### 2. **Logo Verification**
   - Check the visibility and correct display of the website logo on the homepage.

### 3. **Product Navigation**
   - Navigate to the "Products" section from the homepage.
   - Select a product and verify the product page is displayed.

### 4. **Add to Basket**
   - Click the "Add to Basket" button on the product page.
   - Verify that the item is added to the shopping basket.

### 5. **Basket and Checkout Flow**
   - Click on the "View Basket" button to go to the basket page.
   - Verify that the product details are correct in the basket.
   - Click on "Proceed to Checkout" to move to the checkout page.

### 6. **Checkout and Payment**
   - Fill in the required shipping details.
   - Select "Cash on Delivery" as the payment method.
   - Click the "Place Order" button and verify the order confirmation.

## Technologies Used
- **Selenium WebDriver**: Used for automating web interactions.
- **TestNG**: Framework for running the tests.
- **Java**: Programming language used to write the automation scripts.

