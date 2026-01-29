# FoodHub-Management-System
A **desktop-based food management system** developed using **C# (WinForms)** with **MySQL database integration**.
The application is designed to automate food ordering, inventory management, user handling, and payment processing for food service businesses.

---

## 📌 Description

The **Food Hub Management System** streamlines restaurant operations by providing role-based access for Admins, Employees, Chefs, and Customers.
It minimizes manual work, ensures accurate data handling, and improves service efficiency through a centralized database-driven system.

---

## 👤 User Roles & Functionalities

### Admin

* Full system access and control
* Manage all users (Admin, Employee, Chef, Customer)
* Perform CRUD operations on:

  * Users
  * Inventory
  * Menu & Categories
  * Orders
* Monitor system data and overall operations

---

### Employee

* View and manage customer orders
* Update order status
* Add and remove orders
* View customer information
* Access inventory list
* Calculate total order price

---

### Chef

* View pending food orders
* Check food items and quantities
* Update food preparation status:

  * Pending
  * Preparing
  * Ready
* Restricted access to kitchen-related operations only

---

### Customer

* View food menu with prices
* Place food orders
* Select quantity and view total cost
* View order history
* Proceed to payment
* Payment methods:

  * Cash on Delivery (COD)
  * Online Payment
* Delete orders if necessary

---

## 🛠️ Technologies Used

* **Language:** C# (WinForms)
* **Database:** MySQL
* **IDE:** Visual Studio
* **Database Script:** SQL (.txt file)

---

## 🚀 Installation & Setup

Follow the steps below to run the project locally:

### Step 1: Download Project

* Download the complete project folder
* Extract (unzip) the files

---

### Step 2: Database Setup

1. Open **MySQL Workbench**
2. Create a new database (Name: FoodHub Management System)
3. Open **New Query**
4. Open the provided database `.txt` file
5. Copy all SQL code
6. Paste it into the query editor
7. Click **Execute**

✔ All required tables will be created automatically

---

### Step 3: Configure Database Connection

1. Open the project in **Visual Studio**
2. Navigate to:

   ```
   ApplicationHelper.cs
   ```
3. Update the MySQL connection string with your own credentials

Example:

```csharp
server=localhost;user=root;password=YOUR_PASSWORD;database=YOUR_DATABASE_NAME;
```

---

### Step 4: Run the Application

* Build the solution
* Run the project from Visual Studio

✔ The application will start successfully

---

## 📂 Project Structure

* WinForms-based UI
* Centralized database connectivity via `ApplicationHelper.cs`
* Role-based access control
* Normalized relational database design

---

## 🎓 Academic Context

This project was developed as part of the **Object Oriented Programming 2** course and demonstrates:

* GUI application development
* Database integration
* CRUD operations
* Role-based system design

---

## 📄 License

This project is intended for **educational purposes only**.



