# TurfKaro

TurfKaro is a comprehensive turf booking application with three modules: Admin, Owner, and User.  
This app allows users to view and book turf grounds, owners to manage their turfs and bookings, and admins to oversee all activities within the platform.

---

## Features

### User Module
- **Browse Turfs**: View various turfs, check details, and select time slots for booking.  
- **Slot Booking**: Purchase time slots using Razorpay. Users receive a confirmation email with booking details including price, turf name, start time, end time, and a QR code.  
- **Rate Turfs**: Provide ratings for booked turfs.  
- **Become Owner**: Apply to become a turf owner; admins review and approve/reject via email.  

### Owner Module
- **Turf Management**: Add new turfs, manage existing turfs, and view booking details.  
- **Dashboard**: Track transactions and booking statistics with graphs.  
- **Review Management**: Manage reviews left by users.  

### Admin Module
- **Owner Requests**: Approve/reject requests from users who want to become owners.  
- **User and Owner Management**: View and manage all users and owners.  
- **Turf Management**: Monitor and manage all listed turfs.  
- **Transaction Overview**: Access and analyze all platform transactions.  

---

## Technologies Used
- **Frontend**: React, Tailwind CSS, DaisyUI, Redux  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Payments**: Razorpay  
- **Image Hosting**: Cloudinary  

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShrutJainFCB/TurfKaro.git
