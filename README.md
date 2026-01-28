# Simple Login and Dashboard System

A clean, responsive web application for managing student registration and viewing data. This project uses HTML5 and CSS3 to create a cohesive user experience across login, registration, and dashboard views.

## 🚀 Features

* **User Login**: A secure-looking login interface with fields for username and password.
* **Account Registration**: A registration form that includes a confirmation password field to ensure data accuracy.
* **Data Dashboard**: A structured table to display student information, including ID, Name, Email, and Course.
* **Custom Styling**: A centralized stylesheet that manages a professional blue-and-white theme with interactive hover effects.

## 📁 File Structure

* `login.html`: The landing page for existing users.
* `register.html`: The signup page for new users.
* `dashboard.html`: The main view for logged-in users to see student records.
* `style.css`: The primary CSS file containing all layout, color, and component styles.

## 🛠️ Design Details

### Components
* **Containers**: Both login and registration forms are centered using auto-margins and feature a subtle `box-shadow` for a modern "card" feel.
* **Buttons**: The primary action buttons (`.login` and `.create`) use a vibrant blue background (`#007bff`) with smooth transitions on hover.
* **Tables**: The dashboard utilizes a professional dark-header table with row highlighting for better readability.

### Interaction Flow
1.  Users start at **Login**.
2.  New users can navigate to **Sign up** via a text link.
3.  The **Register** button on the signup page is styled as a full-width button to match the login design.
4.  Once "authenticated," the user is directed to the **Dashboard** to view records.

---

*Developed as a frontend demonstration project.*