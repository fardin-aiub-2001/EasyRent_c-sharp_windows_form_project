EasyRent C# Windows Forms Project
Overview
EasyRent is a Windows Forms application built using C# and Microsoft SQL Server. This project provides a structured rental management system with database integration.
Prerequisites
Before running the project, ensure you have the following installed:
- Visual Studio (Latest version recommended)
- Microsoft SQL Server (Ensure it's installed and running)
- SQL Server Management Studio (SSMS) (For database management)
Steps to Run the Project
1. Download the Project
- Clone the repository or download the .sln file.
- Open the solution file (.sln) in Visual Studio.
2. Set Up the Database
- Download the provided database backup file (.bak).
- Open SQL Server Management Studio (SSMS).
- Restore the database using the .bak file:
- Navigate to Databases → Right-click → Restore Database.
- Select the .bak file and follow the restoration steps.
- Ensure the database settings are configured properly.
3. Update Connection String
- Locate the database connection string inside the project:
- Typically found in App.config or inside a database-related class.
- Modify the connection string to match your SQL Server instance, database name, and authentication method.
Example Connection String:
string connectionString = "Data Source=YOUR_SERVER_NAME;Initial Catalog=YOUR_DATABASE_NAME;Integrated Security=True";


4. Run the Project
- Build and Run the project through Visual Studio.
- Ensure the application connects to the database correctly.
Running the Setup from easy rent (folder)
The easy rent folder contains the setup files for deploying the application. Follow these steps to install and run the setup version:
Steps to Install and Run
- Navigate to the easy rent folder
- Locate the setup.exe or installer file inside the folder.
- Run the Installer
- Double-click on setup.exe or the installation file.
- Follow the on-screen instructions to install the application.
- Launch the Application
- After installation, locate the installed application in the Start Menu or Desktop shortcut.
- Open the application and ensure it connects to the database properly.
- Verify Database Connection
- If the application fails to connect, check the database settings and connection string in the configuration files.
- Ensure Microsoft SQL Server is running.
Project Structure
Folders
- Easy Rent (folder) → Contains the source code and .sln file.
- easy rent (folder) → Contains the setup files for deployment.
Additional Notes
- Ensure that Microsoft SQL Server is running before launching the application.
- If facing connection issues, verify the server name, database name, and authentication method in the connection string.
- The project is designed for Windows Forms, making it a desktop-based rental management system.
License
This project is open-source and can be modified as needed.
