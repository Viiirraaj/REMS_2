# 🏘️ Real Estate Management System (REMS)

## 📄 Overview
The **Real Estate Management System (REMS)** is a web-based application designed to simplify property management operations such as property listing, searching, and transaction handling.  
Built using **.NET Framework** and **SQL Server**, REMS provides an efficient and secure platform for users to manage, update, and view real estate data with ease.

---

## 🚀 Key Features
- 🏠 **Property Listings:** Add, edit, and delete property details such as name, type, price, and location.  
- 🔍 **Advanced Search:** Filter properties based on location, price range, and type.  
- 👤 **User Management:** Manage agent and client data securely.  
- 💾 **Database Integration:** Seamless data storage and retrieval using **SQL Server**.  
- 📊 **Dashboard Overview:** Admin panel for monitoring property data and transactions.  
- 🔐 **Authentication & Authorization:** Role-based access control for secure operations.  
- 📱 **Responsive UI:** Clean design adaptable to different screen sizes.

---

## 🧠 Project Objectives
- Digitize and simplify property management processes.  
- Reduce manual errors and improve record-keeping efficiency.  
- Provide an easy-to-use interface for both property agents and clients.  
- Support scalability for larger property networks.  

---

## 🛠️ Tech Stack
| Category | Technology Used |
|-----------|----------------|
| **Frontend** | ASP.NET Web Forms / Razor Pages |
| **Backend** | C# (.NET Framework) |
| **Database** | Microsoft SQL Server |
| **IDE** | Visual Studio |
| **Version Control** | Git & GitHub |
| **Optional Deployment** | IIS Server |

---

## ⚙️ Installation & Setup

Follow these steps to install and run the project successfully on your local system 👇

### Step 1: Install Prerequisites
Before setting up the project, ensure you have:
1. Visual Studio 2019 or later  
2. Microsoft SQL Server (Express or Developer Edition)  
3. SQL Server Management Studio (SSMS)  
4. .NET Framework 4.7 or above  
5. Git  

---

### Step 2: Clone the Repository
Clone the REMS repository from GitHub using the following command:
```bash

git clone https://github.com/Viraj5132/REMS.git

Then navigate into the project folder:

cd REMS

Step 3: Open the Project in Visual Studio

Launch Visual Studio.

Go to File → Open → Project/Solution.

Browse to the folder where you cloned the repository.

Select the file REMS.sln and click Open.

Step 4: Configure the SQL Database

Open SQL Server Management Studio (SSMS).

Connect to your SQL Server instance.

Create a new database:

CREATE DATABASE REMS_DB;


Locate the SQL script file (if available) in the /Database folder and execute it to create the required tables.

In Visual Studio, open the Web.config file and update your connection string:

<connectionStrings>
  <add name="REMS_DB"
       connectionString="Data Source=YOUR_SERVER_NAME;Initial Catalog=REMS_DB;Integrated Security=True"
       providerName="System.Data.SqlClient" />
</connectionStrings>


Replace YOUR_SERVER_NAME with your actual SQL Server instance name.

Step 5: Build the Project

In Visual Studio, go to Build → Build Solution or press Ctrl + Shift + B.

Ensure there are no build errors in the Output window.

Step 6: Run the Application

Click on the Start Debugging button (green play icon) or press F5.

The project will start running in your default web browser.

Default URL example:

http://localhost:xxxx/


You should see the login or homepage of the Real Estate Management System.

Step 7: Login Credentials (Sample)

Use the following sample credentials to test the application (if inserted into the database):

Role	Username	Password	Access
Admin	admin	admin123	Full Access
Agent	agent1	agent123	Property Management
Client	client1	client123	View/Search
Step 8: Using the Application

Admin: Manage users, monitor analytics, view reports.

Agent: Add or update property listings.

Client: Browse and search properties.

Core Modules

Module	Description
🏘 Property Management	CRUD operations on properties
👤 User Management	Add/edit/remove users and assign roles
📈 Reports	Generate system or property reports
🔍 Search	Filter properties by price, location, or type
📦 Transactions	Manage and track property deals
