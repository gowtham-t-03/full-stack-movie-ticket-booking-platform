# Full Stack Movie Ticket Booking Platform

## Overview

A full-stack movie ticket booking platform built using the MERN stack. The application enables users to browse movies, view movie details, watch trailers, book tickets securely, and manage bookings. It also provides an admin dashboard for managing movies, shows, and bookings.

---

## Features

### User Features

- Secure user authentication using Clerk
- Browse available movies
- View movie details
- Watch movie trailers
- Select seats and book tickets
- Secure online payments using Stripe
- View booking history
- Add movies to favourites
- Responsive user interface

### Admin Features

- Admin dashboard
- Add new movies
- Schedule movie shows
- Manage movie listings
- View and manage bookings
- Upload movie posters using Cloudinary

### Backend Features

- RESTful API architecture
- MongoDB database using Mongoose
- Secure authentication middleware
- Stripe payment gateway integration
- Cloudinary image storage
- Email notifications using Nodemailer
- Background job processing using Inngest

---

## Technology Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- React Router DOM
- Axios
- Clerk Authentication
- React Player
- React Hot Toast

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- Clerk
- Stripe
- Cloudinary
- Nodemailer
- Inngest

---

## Project Structure

```
Movie-Ticket-Booking-Platform
│
├── client
│   ├── src
│   ├── public
│   ├── package.json
│   └── vite.config.js
│
├── server
│   ├── configs
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── inngest
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/gowtham-t-03/full-stack-movie-ticket-booking-platform.git
cd full-stack-movie-ticket-booking-platform
```

### Install dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd ../server
npm install
```

---

## Environment Variables

Create a `.env` file inside the `server` directory and configure the following variables:

```env
MONGODB_URI=
CLERK_SECRET_KEY=
CLERK_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
SENDER_EMAIL=
SMTP_PASSWORD=
```

---

## Running the Application

Start the backend

```bash
cd server
npm run dev
```

Start the frontend

```bash
cd client
npm run dev
```

The application will be available at:

```
http://localhost:5173
```

---

## Screenshots

### Home Page

(Add screenshot)

### Movie Details

(Add screenshot)

### Seat Selection

(Add screenshot)

### Booking History

(Add screenshot)

### Admin Dashboard

(Add screenshot)

---

## Key Highlights

- Full-stack MERN application
- Secure authentication using Clerk
- Online payments through Stripe
- Cloudinary integration for media storage
- Booking history management
- Favourite movies functionality
- Email notifications using Nodemailer
- Background job processing using Inngest
- Responsive user interface
- RESTful API architecture
- Role-based admin dashboard

---

## Author

**Telgamalla Gowtham**

