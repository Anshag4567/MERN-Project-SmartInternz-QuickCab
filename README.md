# 🚖 QuickCab - Cab Booking App

QuickCab is a modern cab booking application designed to streamline urban transportation by connecting riders with nearby drivers in real-time. Whether you’re commuting to work or heading out for the weekend, QuickCab ensures a smooth, reliable, and convenient ride every time.

---

## 🌟 Key Features

- 🔐 Secure Rider and Admin Authentication  
- 📍 Real-Time Map Integration for Live Cab Tracking  
- 📅 Ride Booking with Instant Confirmation  
- 📊 Ride History and Feedback System  
- ⚙️ Full Admin Dashboard for Managing Users, Drivers, and Cabs  

---

## 👥 Roles and Responsibilities

### 👤 **Rider (User)**

- **Registration**: Riders can create an account by providing essential information like name, email, and password.  
- **Profile Management**: Riders can update their profile details, including name, email, and password.  
- **Ride Booking**: Users can book a ride by selecting pick-up and drop-off locations and browsing available cabs.  
- **Booking Confirmation**: Once a ride is booked, a confirmation with cab info, driver details, and booking ID is shown.  
- **Ride History**: Riders can view past and upcoming rides, rate experiences, and report issues if necessary.  
- **Feedback**: Users can leave ratings and reviews for drivers and ride experiences.  
- **Logout**: Riders can securely log out of the app when done.  

---

## 🚖 Driver Dashboard

The **Driver Dashboard** allows cab drivers to manage their profile, availability, and ride status in real-time.

### 🔹 Features

- **Driver Profile Overview**
  - `Name`: Displays the driver’s name.
  - `Vehicle`: Shows the vehicle model and registration number.
  - `Rating`: Displays the driver’s rating (e.g., 5.0 ★).
  - `Total Rides`: Number of rides completed.
  - `Availability Status`: Shows whether the driver is Online or Offline.
  - `Go Offline/Online Button`: Toggle to update availability.

- **📍 Live Location Tracking**
  - Real-time location is displayed using [Leaflet](https://leafletjs.com/) with **OpenStreetMap**.
  - Helps in assigning and tracking rides.

- **🚗 Ride Status**
  - **Active Ride**: Displays ride details when a ride is in progress.
  - **No Active Ride**: Shows a message when no current ride is assigned.

- **🕒 Ride History**
  - **Recent Rides**: Displays a list of previously completed rides.
  - If no rides have been completed, a placeholder message is shown.

---


### 🛠️ **Admin**

- **System Management**: Admins oversee the entire cab booking system, ensuring proper functionality and security.  
- **Rider Management**: Admins can view, edit, and delete rider accounts and manage feedback/rating data.  
- **Cab Management**: Admins can add new cabs, update cab info, or remove outdated/inactive listings.  
- **Driver Management**: Admins handle driver profiles, from creation to updates and feedback moderation.  
- **Logout**: Admins can securely log out from the admin dashboard.  

---

## 🗺️ Real-Time Map Feature

QuickCab integrates **real-time mapping and tracking**, allowing users to:

- View nearby available cabs on a live map  
- Track the driver’s location after booking  
- Get accurate ETAs and navigation routes  

This is powered by dynamic map APIs, providing a seamless and interactive user experience.

---

## 🏗️ Tech Stack

**MERN Stack**  
- **MongoDB**  
- **Express.js**  
- **React.js**  
- **Node.js**  

---
**OUTPUT SCREENSHOTS**

![Screenshot 2025-04-13 185017](https://github.com/user-attachments/assets/f34e1d8f-7088-49ca-a126-627a4a091e75)
![Screenshot 2025-04-13 184824](https://github.com/user-attachments/assets/dadd57db-2ed3-4941-ac2e-cc0e401ecbf1)![Screenshot 2025-04-13 184630](https://github.com/user-attachments/assets/20f6aeed-adf9-47bf-8828-f6279b353738)

![Screenshot 2025-04-13 184908](https://github.com/user-attachments/assets/ba9885f4-f7df-4439-b8e1-03189468b04b)
![Screenshot 2025-04-13 184532](https://github.com/user-attachments/assets/c9398f4c-4652-42d3-b8df-7da5842be57b)

![Screenshot 2025-04-13 184824](https://github.com/user-attachments/assets/e7318f01-dc70-4790-9e82-a029af65076c)
![Screenshot 2025-04-13 184753](https://github.com/user-attachments/assets/8178c0d3-a9a9-4bbb-a2a5-ac0487573e5a)


> QuickCab – Bringing you closer to your destination, one ride at a time.
