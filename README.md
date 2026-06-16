# Find a Tail – Full-Stack Pet Adoption Portal

[![HTML5](https://img.shields.io/badge/Language-HTML5-%23E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/Style-CSS3-%231572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![PHP](https://img.shields.io/badge/Backend-PHP-%23777BB4?logo=php&logoColor=white)](https://www.php.net)
[![MySQL](https://img.shields.io/badge/Database-MySQL-%234479A1?logo=mysql&logoColor=white)](https://www.mysql.com)

## 📝 Overview
**Find a Tail** is a data-driven full-stack pet adoption web application developed as a collaborative team project for the **Web Technologies** course at the German Jordanian University. 

The platform connects potential adopters with rescue animals looking for homes through an easy-to-use interface. Instead of rendering static content, the system utilizes an active server-side authentication state and a relational database backend to orchestrate application validation pipelines, dynamic search indexing, and a back-office administration tracking panel.

---

## 🎬 Video Demo
A complete walkthrough of the user signup flow, pet browsing, adoption request process validation triggers, and the live back-office admin dashboard can be viewed here:

[![Watch the Demo](https://img.shields.io/badge/Play_Demo_Video-Click_Here-FF6B6B?style=for-the-badge&logo=youtube&logoColor=white)](https://bit.ly/Pet_Adoption_Portal)

---

## 🚀 Architectural Modules & Features

### 👤 Authenticated Adopter Workspace
* **Session Controls:** Enforces multi-role session verification. Guest users encounter strict form handling middleware guards (`"You must be logged in to submit this form"`) to protect transaction data.
* **Adoption Intake Form:** Collects data-driven metrics including applicant name, age profile checks, historical pet ownership status, and motivational remarks.
* **Self-Service Dashboard:** Enables users to track ongoing application states, interact with custom favorite catalogs, request structured downloads, or clear out historical submissions.

### 🐾 Dynamic Catalog Management
* **Database Streaming:** Restructures and streams active lists dynamically from a relational database, organizing records inside accessible client card modules.
* **Granular Profile Views:** Supports custom item focuses mapping distinct asset labels, description arrays, and age tags directly inside centralized target profile sheets.

### 👑 Back-Office Administration Suite
* **Central Evaluation View:** Pulls active adoption applications into a back-office layout for quick credential assessment.
* **Catalog Intake Engine:** Permits operators to scale up the catalog by injecting new animal entries along with dynamic image files into the application system.
* **Transactional Determinations:** Exposes active execution systems to instantly accept, reject, or wipe data profiles globally across the database with a single action.

---

## 🛠️ Technology Stack

| Layer | Component Technology Details |
| :--- | :--- |
| **Frontend Architecture** | HTML5, CSS3 Grid & Flexbox, Native JavaScript |
| **Server-Side Engine** | PHP (Hypertext Preprocessor) |
| **Database Architecture** | MySQL Relational Database Layer |
| **Development Server** | Apache Server Arrays via Localhost Environments (XAMPP) |
| **System Configurations** | PHP Relational Database Connection Logic (`db.php`) |

---

## 📂 Structural Codebase Inventory

```text
├── 📁 assets/                # Application style assets
│   └── 📁 css/              # Independent template files
├── 📁 img/                   # Database-linked animal asset records and vector graphics
├── 📁 seeds/                 # Relational system data engines
│   └── petSeed.php          # Initial database population script for setup testing
│
├── db.php                   # Centralized database configuration mapping links
├── index.php                # Core public landing layout and entry space
├── style.css                # Global cascading stylesheet defining custom palettes
├── signup.html              # Structural registration layout template
├── userSignup.php           # Post-handling router for incoming registration parameters
│
├── login.php                # Renders user credential identification forms
├── process_login.php        # Validates user authorization arrays and drops session keys
├── process_signup.php       # Sanitizes entry vectors for structural safety parameters
├── signout.php              # Securely clears active tokens and environment states
│
├── view_pet.php             # Pulls and displays structural pet catalog feeds
├── view_za3tar.php          # Renders specific descriptive variables onto profile cards
├── view_pet_za3tar.php      # Synchronized profile component viewport
├── adoption.php             # Stateful application collection forms
├── myAdoption.php           # Renders personal application progress feeds
├── delete.php               # Deletes pending adopter request forms
│
├── adminPage.php            # Unified evaluation portal managing application queues
├── addPet.php               # Admin entry component used to scale catalog inventory
├── deletePet.php            # Drops target profiles permanently from database collections
├── accept.php               # Flips application tracking state to 'Accepted' globally
└── reject.php               # Flips application tracking state to 'Rejected' globally| **Server Processing Core** | PHP (Hypertext Preprocessor) |
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
