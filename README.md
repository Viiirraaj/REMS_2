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

---

## ⚙️ Installation & Setup

### Prerequisites
- Visual Studio (2019 or later)
- Microsoft SQL Server
- .NET Framework 4.7+ installed

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/Viraj5132/REMS.git

   
Open the project in Visual Studio

Go to File → Open → Project/Solution

Select the .sln file in the project folder.

Configure the database

Open SQL Server and create a new database named REMS_DB.

Run the SQL scripts provided in the /Database folder (if available).

Update the connection string in Web.config:

<connectionStrings>
  <add name="REMS_DB" connectionString="Data Source=YOUR_SERVER_NAME;Initial Catalog=REMS_DB;Integrated Security=True" providerName="System.Data.SqlClient"/>
</connectionStrings>


Build and Run

Click on Start Debugging (F5) in Visual Studio.

The app will launch in your default browser.

💻 Usage

Admin Login: Access property management and transaction dashboards.

Agent Login: Manage property listings, update records, and view client details.

Client View: Browse and search for properties with filter options.

🧩 Example Functionalities
Feature	Description
Add Property	Add new property details to the system
Update Property	Modify details of existing properties
Search Property	View and filter available properties
Delete Property	Remove outdated or inactive listings
Admin Reports	View analytics and system usage data
