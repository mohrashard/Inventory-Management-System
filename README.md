
# 📦 Inventory Management System

## 📌 Project Overview
The **Inventory Management System** is a **Service-Oriented Programming (SOP)** project that helps businesses efficiently track and manage inventory. It is built using **C# in Visual Studio** and utilizes **web services** to facilitate seamless communication between different system components.

## ✨ Features
- 📋 **Product Management** – Add, update, and delete inventory items.
- 🔍 **Search & Filter** – Find products by name, category, or stock level.
- 📊 **Stock Tracking** – Monitor available stock and receive alerts for low inventory.
- 🛠️ **Supplier Management** – Store and manage supplier information.
- 📜 **Order Processing** – Generate purchase orders and invoices.
- 👤 **User Authentication** – Secure login system for admin and staff.
- 🔄 **Web Services Integration** – API-based communication between modules.

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS  
- **Backend:** C# (ASP.NET)  
- **Development Tool:** Visual Studio  
- **Database:** SQL Server  
- **Web Services:** RESTful API (ASP.NET Web API)  


## 📁 Project Structure
The project follows a **multi-tier architecture**, separating the business logic, data access, and presentation layers.

```
/InventoryManagementSystem
│── App_Code/
│── Controllers/        # Web API Controllers for handling requests
│── Models/            # Data models representing inventory and users
│── Views/             # HTML & Razor pages for UI
│── WebServices/       # Web services for data exchange
│── wwwroot/           # Static files (CSS, JS)
│── InventoryDB.sql    # Database schema and initial data
│── Program.cs         # Main entry point
│── Startup.cs         # App configuration and service setup
│── README.md
```

## 🚀 Getting Started

### Prerequisites
- Install **Visual Studio (Latest Version)**
- Set up **SQL Server** for database management
- (Optional) Postman for API testing

### Installation

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/mohrashard/inventory-management-system.git
cd inventory-management-system
```

2️⃣ **Open in Visual Studio**  
- Launch **Visual Studio**  
- Open the project folder  
- Restore NuGet packages  

3️⃣ **Set Up Database**
- Open SQL Server Management Studio (SSMS)   

4️⃣ **Run the Application**  
- Click **Run ▶** in Visual Studio  

## 🎮 Example Usage
1. **Login/Register** – Secure authentication for users.
2. **Add Products** – Add new inventory items with details.
3. **Manage Stock** – Update stock levels and check inventory.
4. **Process Orders** – Create purchase orders for suppliers.
5. **Generate Reports** – View sales and stock reports.


## 🔗 API Endpoints 
- `GET /api/products` – Fetch all products
- `POST /api/products` – Add a new product
- `PUT /api/products/{id}` – Update product details
- `DELETE /api/products/{id}` – Remove a product

