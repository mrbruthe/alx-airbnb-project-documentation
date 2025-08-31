# Airbnb Clone Backend - Features & Functionalities

This document outlines the key features and functionalities of the **Airbnb Clone Backend Application**.

## 1. User Management & Authentication
- User registration and login
- Secure password hashing (bcrypt)
- JWT-based authentication
- Role-based access control (guest, host, admin)
- Profile management (update personal info, phone, etc.)

## 2. Property Management
- Hosts can create, update, and delete property listings
- Upload property details (name, description, price per night, location)
- Search/filter properties by location, price, and availability
- Availability management (calendar)

## 3. Booking System
- Guests can request and confirm bookings
- Hosts can accept/reject bookings
- Booking status: pending, confirmed, cancelled
- Automated calculation of total price

## 4. Payment Processing
- Integration with payment gateways (Stripe, PayPal)
- Secure payment transactions
- Track payment status (paid, pending, failed)
- Refund and cancellation support

## 5. Reviews & Ratings
- Guests can leave reviews for properties
- Rating system (1–5 stars)
- Hosts and guests can view feedback

## 6. Messaging System
- Direct messaging between guests and hosts
- Notifications for new messages
- Conversation history

## 7. Admin Dashboard (Optional/Future Scope)
- Manage users, properties, and bookings
- System monitoring and reporting
