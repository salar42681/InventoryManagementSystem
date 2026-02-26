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
<img width="836" height="619" alt="image" src="https://github.com/user-attachments/assets/14acc427-d8d9-41f7-8d29-cfeed920fd50" />
<img width="1881" height="846" alt="image" src="https://github.com/user-attachments/assets/19894e9d-29be-4bb2-841f-4cb9e1895b14" />
<img width="1870" height="851" alt="image" src="https://github.com/user-attachments/assets/ac7d5962-9dea-43c4-b667-398b6b60b351" />
<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/894eebfa-4948-40fc-a2ae-684f5f2759d1" />


## 📄 License
This project is licensed under the MIT License.
