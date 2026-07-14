# Rincón Sabanero: Restaurant POS System

A mobile application and web platform developed as a Point of Sale (POS) system for a traditional cuisine restaurant located in Chia, Cundinamarca, Cololmbia. Its purpose is to manage orders, user roles, and internal operations by integrating Backend-as-a-Service (BaaS) solutions to store data and images in the cloud.

## Description

Rincón Sabanero aims to optimize restaurant operations and customer service by providing a digital solution that streamlines interactions between customers, chefs, and cashiers. The system allows:

- Customers to browse the menu and place orders through the mobile app or web platform, with the ability to use the device's camera to scan QR codes.

- Chefs to receive orders in real time, update their status, and upload product information and images using the phone's camera.

- Cashiers to manage payments, generate invoices, and complete customer orders.

## Objectives

Develop a modern and functional platform for restaurant sales management.

Implement role-based access for different types of users.

Integrate cloud services (Firebase and Supabase) for efficient data and image management.

Create a simple, intuitive, and responsive interface that adapts to both mobile and web devices.

## System Roles

### Customer

User registration and authentication.

Browse the menu with images and prices.

Select products and place orders.

Track order status (preparing, ready, delivered).

### Chef

Upload available products to the database.

Access the active orders dashboard.

Update the status of each order.

View order details, including products, quantities, and customer notes.

### Cashier

Review completed orders.

Process payments and generate invoices.

Monitor daily sales history.

## Technologies and Tools

**Frontend:** React Native (mobile application and web support)

**Backend as a Service (BaaS):**

- Firebase Authentication: User registration and authentication.

- Firestore: Database for orders, users, and chats.

- Supabase: Cloud storage for product images.

**Mobile Development and Build:** Expo
