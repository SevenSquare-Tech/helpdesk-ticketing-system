# 🎟️ Laravel 8 Support Ticketing System

This is a **demo support ticketing system** built with **Laravel 8**, partly generated using [QuickAdminPanel](https://2019.quickadminpanel.com).  
It includes seeded sample data and role-based authentication for Admin and Agent.

---

## 🚀 Features

-   Ticket creation and management
-   Admin and Agent roles
-   Priority and status management
-   Simple and clean interface
-   Ready-to-use seeded demo data

---

## ⚙️ Installation Guide

Follow the steps below to run the project locally:

1. **Clone the repository**

    ```bash
    git clone https://github.com/SevenSquare-Tech/helpdesk-ticketing-system-.git
    ```

2. **Copy the `.env` file**

    ```bash
    cp .env.example .env
    ```

    Update your database credentials and other environment settings in the `.env` file.

3. **Install dependencies**

    ```bash
    composer install
    ```

4. **Generate the application key**

    ```bash
    php artisan key:generate
    ```

5. **Run migrations with seed data**

    ```bash
    php artisan migrate --seed
    ```

    > 💡 This will create tables and insert sample users, tickets, and demo data for testing.

6. **Serve the application**

    ```bash
    php artisan serve
    ```

7. **Access the app**
    - Open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 👤 Demo Login Credentials

| Role  | Email             | Password |
| ----- | ----------------- | -------- |
| Admin | admin@admin.com   | password |
| Agent | agent1@agent1.com | password |

---

## 🧩 Tech Stack

-   **Laravel 8**
-   **MySQL / MariaDB**
-   **Bootstrap 4**
-   **QuickAdminPanel**

---

## 📂 Folder Structure

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
```

---

## 🛠️ Useful Artisan Commands

| Command               | Description                        |
| --------------------- | ---------------------------------- |
| `php artisan migrate` | Run database migrations            |
| `php artisan db:seed` | Seed demo data                     |
| `php artisan serve`   | Start the local development server |

---

⭐ **If you like this project, don’t forget to star the repository!**
