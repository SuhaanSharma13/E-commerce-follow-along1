### Milestone 21 - Address Form Implementation
### 🌟 Overview
Implemented an Address Form page to collect and store user address details.

### 🎯 Learning Goals
Create a frontend form to take user address details.
Capture country, city, address1, address2, zip code, and address type.
### Steps 📝
Created an address form page.
Managed input data using state.
Navigated to the form when clicking "Add Address" in the profile.
This milestone helps in understanding how to build and manage an address form.




### Milestone 23 - Place Order & Select Address Page

### 🌟 Overview

In this milestone, we will implement the “Place Order” feature, allowing users to select a delivery address and finalize their order.

### 🎯 Learning Goals
	•	Add a “Place Order” button to the cart.
	•	Create a “Select Address” page to choose a delivery address.
	•	Write a Mongoose schema to store order details.

### Steps 📝
	1.	Place Order Button:
	•	Add a “Place Order” button to the cart page.
	•	Navigate to the “Select Address” page on click.
	2.	Create Select Address Page:
	•	Display all user addresses on this page.
	•	Allow users to select one as the delivery address.
	3.	Backend Endpoint:
	•	Write an endpoint to fetch all user addresses.
	4.	Mongoose Schema:
	•	Define a schema to store order details, including the selected address and product items.

Why This Matters 🚀

This milestone helps implement essential e-commerce functionality—selecting delivery addresses and storing order details in the backend.



# Milestone 24 🚀  

## Overview  
In this milestone, we will create an Order Confirmation page to display order details.  

## Steps  
1. Show all products being ordered.  
2. Display the selected delivery address.  
3. Show the total cart value.  
4. Add a "Place Order" button at the bottom.  

### Note  
This milestone helps in understanding how to implement the place order functionality.





### Milestone 25 🚀

### Overview

In this milestone, we will create a backend endpoint for placing orders.

### Steps 📝

Create an endpoint to receive products, user details, and address.

Retrieve user ID using the email.

Generate separate orders for each product with the same address.

Store order details in MongoDB using the order schema.

This milestone helps in understanding order placement in the backend.

# Milestone 26: Get User Orders Endpoint

Welcome to Milestone 26! 🎉

In this milestone, we focus on creating a backend endpoint to retrieve all orders placed by a user. This involves setting up an API endpoint that allows users to fetch all their previous orders based on their email.# Milestone 26: Get User Orders Endpoint

# Milestone 27: My Orders Page

Welcome to Milestone 27! 

In this milestone, we focused on creating the frontend page that displays all user orders.

# Milestone 28: Cancel Order Feature

Welcome to Milestone 28!

 In this milestone, we focused on adding a cancel order feature to the my-orders page and creating a backend endpoint for handling order cancellations.

# Milestone 29📝
Created a PayPal Developer Account and logged into the PayPal Developer Dashboard.

Located the Client ID in the sandbox accounts and saved it in the project.

Updated the Order Confirmation Page to include two payment options:

Cash on Delivery (COD)

Online Payment

Implemented radio buttons to toggle between COD and Online Payment.

Set up logic so that PayPal buttons only appear when the Online Payment option is selected.

# Milestone 30📝
Implemented online payment using PayPal API using the client key you created earlier.

Downloaded NPM package called react-paypal-js that will provide an component called PayPalScriptProvider which will display online payment methods like credit or debit card etc.

# Milestone 31: Global State with Redux
Set up Redux to manage the user's email globally.

Key Tasks:
Install react-redux.
Create store.js and userActions.js.
Configure userReducer to store email.
Wrap App with Provider.
This milestone enables centralized state management
