# 🏘️ Real Estate Management System (REMS)

## 📄 Overview
The **Real Estate Management System (REMS)** is a web-based application designed to simplify property management operations such as property listing, searching, and transaction handling.  
Built using **.NET Framework** and **SQL Server**, REMS provides an efficient and secure platform for users to manage, update, and view real estate data with ease.  
This project focuses on creating a centralized digital platform for property agents, clients, and administrators to streamline real estate workflows.

---

## 🚀 Key Features
- 🏠 **Property Listings:** Add, edit, and delete property details such as name, type, price, and location.  
- 🔍 **Advanced Search:** Filter properties based on location, price range, and type.  
- 👤 **User Management:** Manage agent and client data securely.  
- 💾 **Database Integration:** Seamless data storage and retrieval using **SQL Server**.  
- 📊 **Dashboard Overview:** Admin panel for monitoring property data and transactions.  
- 🔐 **Authentication & Authorization:** Role-based access control for secure operations.  
- 📱 **Responsive UI:** Clean and adaptive design for various screen sizes.

---

## 🧠 Project Objectives
- Digitize and simplify property management processes.  
- Reduce manual work and data redundancy through automation.  
- Ensure security, scalability, and real-time performance in operations.  
- Provide separate roles for Admin, Agent, and Client functionalities.  

---

## 🛠️ Tech Stack
| Category | Technology Used |
|-----------|----------------|
| **Frontend** | ASP.NET Web Forms / Razor Pages |
| **Backend** | C# (.NET Framework) |
| **Database** | Microsoft SQL Server |
| **IDE** | Visual Studio |
| **Version Control** | Git & GitHub |
| **Deployment** | IIS Server (Optional) |

---

## ⚙️ Installation & Setup

### Prerequisites
Before running the project, make sure you have:
1. Visual Studio 2019 or later  
2. Microsoft SQL Server (Express or Developer Edition)  
3. SQL Server Management Studio (SSMS)  
4. .NET Framework 4.7 or higher  
5. Git installed on your system  

---

### Steps to Setup

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Viraj5132/REMS.git
cd REMS
```

#### 2️⃣ Open the Project in Visual Studio
```bash
1. Launch Visual Studio.
2. Go to File → Open → Project/Solution.
3. Select the "REMS.sln" file located in the cloned folder.
```

#### 3️⃣ Configure the SQL Database
```bash
1. Open SQL Server Management Studio (SSMS).
2. Connect to your SQL Server instance.
3. Create a new database:
```
```sql
CREATE DATABASE REMS_DB;
```
```bash
4. If a .sql script is provided inside /Database folder, run it to create tables.
5. Open Web.config file in Visual Studio.
6. Replace the connection string with:
```
```xml
<connectionStrings>
  <add name="REMS_DB" 
       connectionString="Data Source=YOUR_SERVER_NAME;Initial Catalog=REMS_DB;Integrated Security=True" 
       providerName="System.Data.SqlClient" />
</connectionStrings>
```
> ⚠️ Replace `YOUR_SERVER_NAME` with your SQL Server instance name.

---

#### 4️⃣ Build and Run the Project
```bash
1. In Visual Studio, go to Build → Build Solution (or press Ctrl + Shift + B).
2. Once the build is successful, click Start Debugging (F5).
3. The project will open in your default browser.
4. Default URL example:
   http://localhost:xxxx/
```

---

#### 5️⃣ Login (Sample Credentials)
Use these default credentials to explore the system (if data seeded):

| Role | Username | Password | Access |
|------|-----------|-----------|--------|
| Admin | admin | admin123 | Full access |
| Agent | agent1 | agent123 | Manage listings |
| Client | client1 | client123 | Browse/search properties |

---

## 💻 Usage
Once logged in:
- **Admin:** Manage users, view system analytics, monitor property data.  
- **Agent:** Add, edit, or delete property listings.  
- **Client:** View, filter, and search properties.

| Module | Description |
|---------|-------------|
| 🏘 Property Management | CRUD operations for all property listings |
| 👥 User Management | Add/edit/remove users and assign roles |
| 📈 Reports | View and export property data |
| 🔍 Search System | Real-time property search with filters |
| 📦 Transactions | Manage deals and records |

---

## 📸 Screenshots (Optional)
Add your screenshots in the `screenshots/` folder and reference them like this:

```markdown
![Dashboard](./screenshots/dashboard.png)
![Property Listing](./screenshots/property_list.png)
![Add Property](./screenshots/add_property.png)
```

---

## 🧠 Learning Outcomes
```bash
1. Developed hands-on experience with ASP.NET and SQL Server.
2. Implemented full CRUD operations with real database connectivity.
3. Gained exposure to authentication and authorization workflows.
4. Strengthened debugging and version control skills (Git/GitHub).
```

---

## 🧩 Future Enhancements
```bash
1. Integrate Google Maps API for property location display.
2. Implement payment gateway for property booking.
3. Add React.js frontend for a more modern UI experience.
4. Generate PDF reports for analytics and export functionality.
```

---

## 🤝 Contribution
Contributions are always welcome!  
To contribute:
```bash
1. Fork this repository.
2. Clone your forked version:
   git clone https://github.com/<your-username>/REMS.git
3. Create a new branch:
   git checkout -b feature/YourFeatureName
4. Commit changes:
   git commit -m "Added a new feature"
5. Push changes:
   git push origin feature/YourFeatureName
6. Create a Pull Request for review.
```

---

## 📜 License
This project is open-source and available under the **MIT License**.  
Feel free to use, modify, and distribute this project with proper attribution.

---

## 👨‍💻 Author
**👤 Viraj Santosh Shinde**  
📍 Thane, Maharashtra, India  
🎓 Master’s in Computer Science – Ramnarain Ruia College  
💼 Web Development Intern – Hivyu Prive  
📧 [virajshinde911@gmail.com](mailto:virajshinde911@gmail.com)  
🔗 [GitHub Profile](https://github.com/Viiirraaj)  
💼 [LinkedIn Profile](https://www.linkedin.com/in/viraj-shinde-31539a301/) 

---

## ⭐ Acknowledgments
```bash
- Special thanks to my professors and peers for their support.
- Inspired by real-world property management platforms.
- If you found this project helpful, please ⭐ star the repository!
```
