# 🚗 Vehicle Service Management System

## 📌 Project Overview

The **Vehicle Service Management System** is a web-based application developed to simplify and automate the activities of a vehicle service center. The system helps manage customer information, vehicle details, service records, mechanics, service status, and service costs.

Instead of maintaining service records manually in notebooks or spreadsheets, this system stores the information in a database and provides an easy-to-use web interface for managing vehicle service operations.

---

## 🎯 Objectives

The main objectives of this project are:

* To maintain customer details efficiently.
* To store and manage vehicle information.
* To record vehicle service details.
* To assign mechanics to service tasks.
* To track service status.
* To maintain vehicle service history.
* To record service costs.
* To reduce manual paperwork.
* To provide quick access to service information.
* To improve the efficiency of a vehicle service center.

---

## ✨ Features

### 👤 Customer Management

* Add new customers.
* Store customer name, phone, email, and address.
* Maintain customer records.

### 🚘 Vehicle Management

* Register customer vehicles.
* Store registration number.
* Store vehicle brand and model.
* Record fuel type.
* Link vehicles with customers.

### 🔧 Service Management

* Add new service records.
* Select the vehicle for servicing.
* Select the service type.
* Record service date.
* Add problem/service description.
* Assign a mechanic.
* Track service status.
* Record service cost.

### 📋 Service History

* View previous service records.
* View vehicle registration numbers.
* View service type and date.
* View assigned mechanic.
* View service status and cost.
* Delete service records when required.

### 📊 Dashboard

The dashboard provides an overview of:

* Total customers
* Total vehicles
* Total services
* Recent service records

---

## 🛠️ Technologies Used

### Frontend

* **HTML5**
* **CSS3**
* **Jinja2 Templates**

### Backend

* **Python**
* **Flask Framework**

### Database

* **SQLite**

### Development Tools

* **Visual Studio Code**
* **Git**
* **GitHub**

---

## 🏗️ System Architecture

```text
+----------------------+
|       USER           |
+----------+-----------+
           |
           ↓
+----------------------+
|      FRONTEND        |
|    HTML + CSS        |
|      Jinja2          |
+----------+-----------+
           |
           ↓
+----------------------+
|       BACKEND        |
|   Python + Flask     |
+----------+-----------+
           |
           ↓
+----------------------+
|       DATABASE       |
|       SQLite         |
+----------------------+
```

---

## 📁 Project Structure

```text
VehicleServiceManagement/
│
├── app.py
│
├── vehicle_service.db
│
├── templates/
│   ├── index.html
│   ├── add_customer.html
│   ├── add_vehicle.html
│   ├── add_service.html
│   └── services.html
│
└── static/
    └── style.css
```

---

## 🗄️ Database Tables

### Customer Table

| Field   | Description           |
| ------- | --------------------- |
| id      | Customer ID           |
| name    | Customer name         |
| phone   | Customer phone number |
| email   | Customer email        |
| address | Customer address      |

### Vehicle Table

| Field           | Description                 |
| --------------- | --------------------------- |
| id              | Vehicle ID                  |
| customer_id     | Associated customer         |
| registration_no | Vehicle registration number |
| brand           | Vehicle brand               |
| model           | Vehicle model               |
| fuel_type       | Type of fuel                |

### Service Table

| Field        | Description                 |
| ------------ | --------------------------- |
| id           | Service ID                  |
| vehicle_id   | Associated vehicle          |
| service_type | Type of service             |
| service_date | Date of service             |
| description  | Service/problem description |
| mechanic     | Assigned mechanic           |
| status       | Service status              |
| cost         | Service cost                |

---

## 🔄 Application Workflow

```text
Customer Registration
        ↓
Vehicle Registration
        ↓
Book/Add Service
        ↓
Vehicle Inspection
        ↓
Assign Mechanic
        ↓
Perform Service
        ↓
Update Service Status
        ↓
Record Service Cost
        ↓
Store Service History
```

---

## 💻 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/VehicleServiceManagement.git
```

### Step 2: Open the Project

Open the project folder using **Visual Studio Code**.

### Step 3: Install Flask

Open the VS Code terminal and run:

```bash
pip install flask
```

### Step 4: Run the Application

```bash
python app.py
```

### Step 5: Open in Browser

Open:

```text
http://127.0.0.1:5000
```

---

## 🖥️ Application Pages

### Dashboard

The dashboard displays the total number of customers, vehicles, and services.

### Add Customer

Used to register a new customer.

### Add Vehicle

Used to register a vehicle and associate it with a customer.

### Add Service

Used to create a service record for a vehicle.

### Service History

Displays all recorded vehicle service details.

---

## 📈 Future Enhancements

The following features can be added in future versions:

* 🔐 Admin login and authentication
* 👨‍🔧 Separate mechanic management
* 📅 Online service appointment booking
* 📦 Spare-parts inventory management
* 🧾 Automatic invoice generation
* 💳 Online payment integration
* 📧 Email notifications
* 📱 Mobile-friendly interface
* 📊 Advanced service reports
* 🔍 Advanced search and filtering
* ⭐ Customer feedback and ratings
* 🛠️ Complete service history for each vehicle

---

## 🎓 Academic Project

This project is suitable for a **college-level web development/database project**.

### Project Title

**Vehicle Service Management System**

### Project Type

**Web-Based Application**

### Frontend

**HTML, CSS, Jinja2**

### Backend

**Python Flask**

### Database

**SQLite**

### IDE

**Visual Studio Code**

---

## 👨‍💻 Author

**Pavisha S**

Vehicle Service Management System

---

## 📜 License

This project is created for educational and academic purposes.
