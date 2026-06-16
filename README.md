# Find a Tail – Full-Stack Pet Adoption Portal

[![HTML5](https://img.shields.io/badge/Language-HTML5-%23E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/Style-CSS3-%231572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![PHP](https://img.shields.io/badge/Backend-PHP-%23777BB4?logo=php&logoColor=white)](https://www.php.net)
[![MySQL](https://img.shields.io/badge/Database-MySQL-%234479A1?logo=mysql&logoColor=white)](https://www.mysql.com)

## 📝 Overview

**Find a Tail** is a full-stack pet adoption web application developed as a collaborative team project for the **Web Technologies** course at the German Jordanian University.

The platform connects potential adopters with pets looking for homes through an intuitive web interface. Users can browse available pets, view detailed profiles, submit adoption requests, save favorites, and track their applications. Administrators can manage pet listings and review adoption requests through a dedicated dashboard.

The application was built using **PHP, MySQL, HTML, CSS, and JavaScript**, with server-side authentication, session management, and a relational database backend.

---

## 🎬 Video Demo

A complete walkthrough of the user signup flow, pet browsing, adoption request process, and admin dashboard can be viewed here:

[![Watch the Demo](https://img.shields.io/badge/Play_Demo_Video-Click_Here-FF6B6B?style=for-the-badge&logo=youtube&logoColor=white)](https://bit.ly/Pet_Adoption_Portal)

---

## 🚀 Features

### 👤 User Features

- User registration and login system.
- Session-based authentication and access control.
- Browse available pets dynamically from a MySQL database.
- View detailed pet profiles with descriptions and images.
- Save pets to favorites.
- Submit adoption requests through a structured application form.
- Track adoption request status and history.
- Download pet information.

### 🐾 Pet Management

- Dynamic pet catalog powered by a relational database.
- Individual pet profile pages.
- Image and information management for each listing.
- Database-driven content updates.

### 👑 Administrator Features

- Dedicated admin dashboard.
- Add new pets to the adoption catalog.
- Manage existing pet listings.
- Review submitted adoption requests.
- Accept or reject adoption applications.
- Remove pets and applications when necessary.

### 🔒 Security & Validation

- Session-based user authentication.
- Server-side form validation using PHP.
- Protected administrative functionality.
- Login requirement before submitting adoption requests.

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| Frontend | HTML5, CSS3, JavaScript |
| Backend | PHP |
| Database | MySQL |
| Local Development | XAMPP / Apache |
| Database Connection | PHP MySQL connection through `db.php` |

---

## 📂 Project Structure

```text
├── assets/                 # Application assets
│   └── css/                # Styling files
├── img/                    # Pet images and visual assets
├── seeds/                  # Database seed files
│   └── petSeed.php         # Initial pet data insertion script
│
├── db.php                  # Database connection
├── index.php               # Landing page
├── style.css               # Main stylesheet
├── signup.html             # User registration page
├── userSignup.php          # Registration handling
│
├── login.php               # Login page
├── process_login.php       # Login processing
├── process_signup.php      # Signup processing
├── signout.php             # Logout handling
│
├── view_pet.php            # Pet listing page
├── view_za3tar.php         # Pet details page
├── view_pet_za3tar.php     # Pet profile view
├── adoption.php            # Adoption request form
├── myAdoption.php          # User adoption tracking page
├── delete.php              # Delete adoption request
│
├── adminPage.php           # Admin dashboard
├── addPet.php              # Add pet page
├── deletePet.php           # Delete pet handling
├── accept.php              # Accept adoption request
└── reject.php              # Reject adoption request
