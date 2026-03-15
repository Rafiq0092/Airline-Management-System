# Airline Management System

An Airline Management System built using **HTML, CSS, and JavaScript**.  
This project allows users to **register, log in, book tickets, and manage flight reservations**.  
User data and booking details are stored using **Local Storage**, making the project simple, interactive, and easy to run in a browser.

---

## Features

- User Registration System
- User Login Authentication
- Login allowed only after registration
- Flight Booking Functionality
- Ticket Reservation Management
- View reserved flights
- Store user and booking data in Local Storage
- Simple and user-friendly interface

---

## Technologies Used

- **HTML** – for structuring the web pages  
- **CSS** – for styling and layout  
- **JavaScript** – for logic and functionality  
- **Local Storage** – for storing user registration and booking data  

---

## Project Functionality

This project works as a basic airline reservation system where users must first create an account before logging in.

### Registration
- A new user must register first
- User details are saved in Local Storage
- If the user is not registered, login is not allowed

### Login
- Only registered users can log in
- The system checks stored credentials from Local Storage
- Invalid users cannot access the booking system

### Ticket Booking
- Logged-in users can book flight tickets
- Booking details are stored in Local Storage
- Users can reserve flights based on available options

### Reservation Tracking
- The system can show how many flights are reserved
- Users can view their booking/reservation details

---

## How It Works

1. User opens the project in the browser
2. User registers an account
3. Registered user logs in
4. After login, user can book tickets
5. Booking and user details are saved in Local Storage
6. Reserved flights and booking data can be viewed later

---

## Advantages of This Project

- Easy to understand and use
- Beginner-friendly web development project
- No external database required
- Works directly in the browser
- Good project for learning authentication and Local Storage

---

## Project Structure

```bash
Airline-Management-System/
│── index.html
│── style.css
│── script.js
│── README.md
