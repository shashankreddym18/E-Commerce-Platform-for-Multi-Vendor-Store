# E-Commerce-Platform-for-Multi-Vendor-Store

## Overview

This project is a fully functional multi-vendor e-commerce platform that enables users to register, post products, manage carts, and complete transactions securely. The platform is designed to support multiple vendors, allowing them to manage their own products and orders independently while providing a seamless shopping experience for customers.

## Features

- **User Registration and Authentication:**
  - Secure user authentication using Firebase.
  - JWT token-based authentication for secure sessions.
  
- **Vendor Management:**
  - Vendors can register, log in, and manage their own product listings.
  - Vendors can track orders and manage inventory.

- **Product Posting and Cart Management:**
  - Users can browse products, add them to the cart, and proceed to checkout.
  - Vendors can post and update product details.

- **Secure Payments:**
  - Integrated Razorpay for secure payment processing.
  
- **Real-time Order Notifications:**
  - Integrated Twilio API for sending real-time order status notifications via SMS.

- **RESTful APIs:**
  - Developed REST APIs for efficient client-server communication.
  - JWT-based authentication ensures secure access to resources.

- **User Interface:**
  - Utilized Material UI for a consistent and intuitive interface.
  - Focused on delivering a visually appealing and user-centric experience.

## Usage

### User Registration:

- Sign up as a vendor or customer.
- Log in using Firebase authentication.

### Product Management:

- Vendors can add, update, or remove products.
- Customers can browse and add products to their cart.

### Checkout Process:

- Proceed to checkout and complete payment using Razorpay.
- Receive real-time order updates via Twilio SMS.

## Technology Stack

- **Frontend:** React.js, Material UI
- **Backend:** Node.js, Express.js
- **Database:** Firebase Firestore
- **Payment Gateway:** Razorpay
- **Notifications:** Twilio API
- **Authentication:** Firebase Auth, JWT

## Future Improvements

- Implementing a review and rating system for products.
- Adding support for multiple payment gateways.
- Enhancing vendor analytics with detailed sales reports.

## Contributions

Contributions are welcome! Please fork this repository and submit pull requests for any improvements or new features.
