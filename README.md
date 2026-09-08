# MediBook — Doctor Appointment & Healthcare Platform

MediBook is a full-stack doctor appointment and healthcare platform built using the MERN stack. It provides separate interfaces for patients, doctors, and administrators, allowing users to find doctors, book appointments, manage appointments, and make online payments.

## Features

### Patient

* User registration and login
* Browse doctors
* Filter doctors by speciality
* View doctor profiles
* Select available appointment slots
* Book and cancel appointments
* View and manage appointments
* Online payment integration
* Manage user profile

### Doctor

* Doctor login
* Doctor dashboard
* View appointments
* Manage appointment status
* View earnings
* Update doctor profile

### Admin

* Admin authentication
* Add and manage doctors
* View appointments
* Manage platform data

## Tech Stack

* **Frontend:** React.js, React Hooks
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, MongoDB Atlas
* **Authentication:** JWT, bcrypt
* **Payments:** Stripe, Razorpay
* **Other:** REST APIs, Cloudinary

## Project Structure

```text
MediBook/
├── admin/
├── frontend/
├── backend/
└── README.md
```

## Installation

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd MediBook
```

### 2. Install Dependencies

Install the dependencies for the frontend, backend, and admin panel.

```bash
npm install
```

Run the same command inside the required project directories.

### 3. Environment Variables

Create `.env` files in the required directories and add your MongoDB, JWT, payment, and other required credentials.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret
```

**Do not commit your `.env` files or secret credentials to GitHub.**

### 4. Run the Application

Start the backend:

```bash
npm run server
```

Start the frontend:

```bash
npm run dev
```

Start the admin panel using its configured development command.

## Authentication

The application uses **JWT-based authentication** for user and doctor login sessions. Passwords are securely hashed using **bcrypt**.

## Payments

The platform supports online payments using **Stripe** and **Razorpay**.

## Database

MongoDB is used to store application data, with **MongoDB Atlas** used for cloud database hosting.

## Author

**Aneesh Bera**

MCA Student | Full-Stack Developer | MERN Stack

