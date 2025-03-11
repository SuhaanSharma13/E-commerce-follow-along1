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