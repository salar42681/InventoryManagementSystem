# 📦 Inventory Management System

A desktop-based Inventory Management System built with **Windows Forms (C#)** 
and **Microsoft SQL Server**, designed to help businesses manage their 
products, stock levels, suppliers, and sales efficiently.

## 🚀 Features
- Add, update, and delete products
- Real-time stock level tracking
- Manage suppliers and purchase orders
- Sales and inventory reporting
- Low stock alerts
- User login & role-based access

## 🛠️ Tech Stack
- **Frontend/UI:** Windows Forms (C# .NET)
- **Backend:** C# (.NET Framework / .NET Core)
- **Database:** Microsoft SQL Server (MS SQL)
- **IDE:** Visual Studio

## ⚙️ Prerequisites
- Visual Studio 2019/2022
- .NET Framework (version you used)
- Microsoft SQL Server
- SQL Server Management Studio (SSMS)

## 🗄️ Database Setup
1. Open **SSMS** and connect to your SQL Server localhost
2. Clone the database provided `database/inventorydb.sql`


## 🚀 How to Run
1. Clone the repo:
   `git clone https://github.com/salar42681/inventory-management-system.git`
2. Open the `.sln` file in **Visual Studio**
3. Set up the database (see above)
4. Build and run the project (`F5`)
5. Admin Credential 
   Username:Admin
   Password:Admin1234
6. Cashier Credential
   Username:Admin1
   Password:Admin1234

## ⚙️ Configuration
1. Open App.config you will see this
<appSettings>
	<add key="SMTP_USER" value="Your@email.com" />
	<add key="SMTP_PASS" value="16 digit code" />
</appSettings>

2. Here in the Smtp_user value="Add Your Email"
   And in Smtp_pass add 16 Digit app code generated from google

## How to generate Google App 8 Digit Code
Step 1: Enable 2-Step Verification

Go to myaccount.google.com
Click Security from the left menu
Under "How you sign in to Google" enable 2-Step Verification

Step 2: Generate App Password

Go to myaccount.google.com/apppasswords
Sign in if asked
In "App name" type anything e.g. Inventory App
Click Create
Google will show you a 16-character password like:
xxxx xxxx xxxx xxxx

## 📸 Screenshots
<img width="1881" height="849" alt="image" src="https://github.com/user-attachments/assets/c165dfcd-b2ad-45d6-8ba5-433b7d4cf483" />
<img width="1885" height="844" alt="image" src="https://github.com/user-attachments/assets/533272a0-d598-497f-8ba8-3cb2008d1cf0" />
<img width="1878" height="855" alt="image" src="https://github.com/user-attachments/assets/25c433d2-f43a-48a8-9096-4d95285e86e4" />
<img width="722" height="945" alt="image" src="https://github.com/user-attachments/assets/291897a6-a2cc-4c0e-a087-254585340116" />



## 📄 License
This project is licensed under the MIT License.
