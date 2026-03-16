# Fullstack Food Ordering Website (MERN + Stripe)

A complete **food delivery web application** built using **React.js, Node.js, Express.js, MongoDB**, and **Stripe payment gateway**.  
This full-stack project includes a **frontend website**, **admin panel**, and **backend server** with user authentication, shopping cart, and real-time order updates.

---

## Project Overview
This project allows users to:
- Create an account and log in
- Browse food items and add them to a shopping cart
- Place orders and pay online using Stripe
- Track order status in real-time
- Admin panel to manage food items and orders

---

## Tech Stack
- **Frontend:** React.js, Redux, CSS, HTML  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **Payment Gateway:** Stripe  
- **Other:** Socket.io for real-time updates

---

## Features
- **User Authentication:** Sign up / login  
- **Shopping Cart:** Add/remove items and place orders  
- **Online Payment:** Stripe integration for payments  
- **Admin Panel:** Manage food items, view and update orders  
- **Responsive Design:** Works on mobile, tablet, and desktop  
- **Real-Time Updates:** Order status updates for users

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Diyu30/fullstack-food-delivery.git

2. Navigate to the backend folder and install dependencies:
```bash
cd backend
npm install

3. Create a .env file in the backend folder using .env as a reference:
```bash
JWT_SECRET="your_jwt_secret_here"
STRIPE_SECRET_KEY="your_stripe_test_key_here"
