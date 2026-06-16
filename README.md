# Find a Tail – Full-Stack Pet Adoption Portal

[![HTML5](https://img.shields.io/badge/Language-HTML5-%23E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/Style-CSS3-%231572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![PHP](https://img.shields.io/badge/Backend-PHP-%23777BB4?logo=php&logoColor=white)](https://www.php.net)
[![MySQL](https://img.shields.io/badge/Database-MySQL-%234479A1?logo=mysql&logoColor=white)](https://www.mysql.com)

## 📝 Overview
**Find a Tail** is a data-driven full-stack web application built to streamline and secure the process of animal rescue and pet adoption. Developed as a collaborative team project for the *Web Technologies* curriculum, this platform features an intuitive public-facing interface for prospective adopters alongside an isolated, functional back-office administrative platform.

The system utilizes session-based authorization structures, secure form handling pipelines, and a structured **MySQL** relational database state managed completely by custom **PHP** backend logic operations.

---

## 🎬 Video Demo
Since this repository serves as a public source-code archive, a complete walkthrough of the user signup flow, dynamic pet browsing, adoption form validation triggers, and the back-office administrative decisions panel can be viewed here:

[![Watch the Demo](https://img.shields.io/badge/Play_Demo_Video-Click_Here-FF6B6B?style=for-the-badge&logo=youtube&logoColor=white)](https://bit.ly/Pet_Adoption_Portal)

---

## 🚀 Architectural Modules & Features

### 🔐 User Management & Validation Pipelines
* **Secure Registration (`signup.html`, `userSignup.php`):** Renders clean user creation templates connected directly to backend data targets.
* **Authentication Middleware (`process_login.php`, `process_signup.php`):** Implements backend server-side validation checks to handle user requests, sanitize parameter injection strings, and sign secure session keys.
* **Session Exits (`signout.php`):** Erases global server array session blocks securely to prevent local context exploits.

### 🐾 Dynamic Pet Catalog & Adopter Space
* **Dynamic Feed Rendering (`view_pet.php`):** Queries and streams active relational database listings to dynamically display active animal lists inside modular client view container components.
* **Target Profile Focus (`view_za3tar.php`, `view_pet_za3tar.php`):** Pulls explicit target profiles into focus screens detailing specialized health, description, and asset mappings.
* **Stateful Form Checks (`adoption.php`):** Collects applicant experience profiles, age limits, and adoption motivations under condition guards (*"You must be logged in to submit this form"*).
* **Track Workspace (`myAdoption.php`):** Allows users to review ongoing review queues, track status changes, or drop application entities (`delete.php`).

### 👑 Back-Office Administrative Dashboard
* **Central Evaluation View (`adminPage.php`):** Collects submitted application fields in clean back-office views for review.
* **Intake Content Creation (`addPet.php`):** Permits operators to inject new animal entities along with asset parameters directly into the live application pipeline database catalog.
* **Status Controls (`accept.php`, `reject.php`, `deletePet.php`):** Exposes transactional command controls to update database states globally with a single click.

---

## 🛠️ Technology Stack

| Layer | Component Technology Details |
| :--- | :--- |
| **Frontend Layouts** | HTML5, CSS3 Architecture Frameworks (`style.css`), Native JavaScript |
| **Server Processing Core** | PHP (Hypertext Preprocessor) |
| **Database Management** | MySQL Relational Database Layer (`db.php`) |
| **Database Initializers** | PHP Database Population Engineering Scripting (`seeds/petSeed.php`) |
| **Deployment Engine** | Localhost Environment via Apache Server Arrays |

---

## 📂 Structural Codebase Inventory

Based on the official directory structures, the active repository layout is mapped as follows:

```text
├── 📁 assets/                # App asset collections
│   └── 📁 css/              # Core cascading styling sheets
├── 📁 img/                   # Static application background graphics and animal photo vectors
├── 📁 seeds/                 # Relational system data engines
│   └── petSeed.php          # Database population tool for raw initialization tracking
│
├── ⚙️ Base Configurations & Core Pages
│   ├── db.php               # Houses target server parameters and database connections
│   ├── index.php            # Primary landing workspace entry layout
│   ├── style.css            # Explicit globally distributed application stylesheets
│   ├── signup.html          # Structural onboarding markup form
│   └── userSignup.php       # Processes registration inputs for database submission
│
├── 👤 Adopter Portal Modules
│   ├── login.php            # Presents credential verification prompts
│   ├── process_login.php    # Authorizes system entries and maps session variables
│   ├── view_pet.php         # Generates active lists from pet catalog records
│   ├── view_za3tar.php      # Compiles granular visual descriptive files for specific profiles
│   ├── adoption.php         # Secure request collection and input validation forms
│   ├── process_signup.php   # Internal request system logging validation targets
│   ├── myAdoption.php       # Renders trackable historical submission elements
│   ├── delete.php           # Drops active requests from personal tracking lines
│   └── signout.php          # Clears ongoing environment tokens and returns to home
│
└── 👑 Back-Office Admin Actions
    ├── adminPage.php        # Unified dashboard handling application queues
    ├── addPet.php           # Catalog expander view to process new animal entries
    ├── deletePet.php        # Removes listed profiles permanently from catalog records
    ├── accept.php           # Updates database application tracking variables to 'Accepted'
    └── reject.php           # Updates database application tracking variables to 'Rejected'
