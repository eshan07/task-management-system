# 🚀 **Task Management System API**

This is a **Task Management System API** built using **Laravel 11** as part of a **learning project** and **technical assessment**. The goal was to demonstrate my understanding of **Laravel concepts**, **API development**, and **software design principles**.

---

## 📑 **Table of Contents**

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup and Installation](#setup-and-installation)
5. [Environment Configuration](#environment-configuration)
6. [Database Migration](#database-migration)
7. [API Endpoints](#api-endpoints)
8. [Testing](#testing)

---

## 📖 **1. Project Overview**

The Task Management System allows authenticated users to **create**, **read**, **update**, and **delete tasks**. Users can also **filter tasks by status** and **sort them by due date**. The system follows **Laravel best practices** and includes **unit and feature tests** to ensure the reliability of the application.

This project helped me understand and practice:
- API Design
- Laravel Service Container & Service Providers
- Middleware and Authentication
- Testing (Unit & Feature)

---

## 🌟 **2. Features**

- ✅ **User Authentication:** Register, Login, Logout
- ✅ **Task Management:** Create, Read, Update, Delete tasks
- ✅ **Task Filtering:** By status (Pending, In Progress, Completed)
- ✅ **Task Sorting:** By due date
- ✅ **RESTful API Endpoints:** Structured API for integration
- ✅ **Validation:** Proper request validation
- ✅ **Testing:** Unit and Feature tests for reliability

---

## 🛠️ **3. Technologies Used**

- **Laravel 11**
- **PHP 8.x**
- **MySQL**
- **Sanctum** (for API Authentication)
- **Composer**
- **PHPUnit**

---

## 💻 **4. Setup and Installation**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/task-management-system.git
   cd task-management-system
   ```

2. **Install Dependencies:**
   ```bash
   composer install
   ```

3. **Generate Application Key:**
   ```bash
   php artisan key:generate
   ```

4. **Copy Environment File:**
   ```bash
   cp .env.example .env
   ```

---

## ⚙️ **5. Environment Configuration**

Update the `.env` file with your database and other necessary configurations:

```env
APP_NAME=TaskManagementSystem
APP_ENV=local
APP_KEY=base64:xxx
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=task_management
DB_USERNAME=root
DB_PASSWORD=

SANCTUM_STATEFUL_DOMAINS=localhost
```

---

## 🗄️ **6. Database Migration**

1. **Run Database Migrations:**
   ```bash
   php artisan migrate
   ```

2. **Seed the Database (Optional):**
   ```bash
   php artisan db:seed
   ```

3. **Start the Application:**
   ```bash
   php artisan serve
   ```

---

## 📡 **7. API Endpoints**

### 🛠️ **Authentication**
- **POST /api/register:** Register a new user
- **POST /api/login:** Log in a user
- **POST /api/logout:** Log out a user

### 📝 **Tasks**
- **GET /api/tasks:** List all tasks
- **POST /api/tasks:** Create a new task
- **GET /api/tasks/{id}:** Get a specific task
- **PUT /api/tasks/{id}:** Update a task
- **DELETE /api/tasks/{id}:** Delete a task

### 🔍 **Filtering & Sorting**
- **GET /api/tasks?status=Pending:** Filter tasks by status
- **GET /api/tasks?sort_by=due_date:** Sort tasks by due date

---

## 🧪 **8. Testing**

1. **Run Unit Tests:**
   ```bash
   php artisan test --testsuite=Unit
   ```

2. **Run API Tests:**
   ```bash
   php artisan test --testsuite=Feature
   ```

3. **Run All Tests:**
   ```bash
   php artisan test
   ```

---

## 📬 **Contact Information**

For any feedback or questions, feel free to reach out:  
**📧 Email:** [mdeshan307@gmail.com](mailto:mdeshan307@gmail.com)

---

Thank you for reviewing my project! 😊🚀
