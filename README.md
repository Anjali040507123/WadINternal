✅ Week 1, 2, 3, 4 (Frontend Basics)
🌐 Run using Live Server
Open your project folder in VS Code
Create HTML/CSS/JS files as required
Right-click on index.html
Select “Open with Live Server”
Browser will automatically open the project
Make changes in code → save → auto reload happens
✅ Week 5 (Java + MySQL CRUD App in Eclipse)
☕ Eclipse Setup + Database Connection
Open Eclipse
Go to: File → New → Java Project
Enter project name → Finish
📦 Create Package & Class
Inside src → Right-click → New → Package
Name it (example: com.app)
Right-click package → New → Class
Name: CRUDApp
Paste your Java CRUD code
🔗 Add MySQL Connector
Right-click project → Build Path → Configure Build Path
Go to Libraries
Click Classpath → Add External JAR
Select MySQL Connector JAR
Click Apply and Close
🗄️ MySQL Setup
Open MySQL / Workbench
Run:
CREATE DATABASE studentdb;
USE studentdb;
▶️ Run Project
Run Java program in Eclipse
Verify database operations
✅ Week 6 (XML - Error Practice)
🧾 XML File Editing
Open XML file
Remove commented sections
Ensure syntax errors appear for practice
Validate XML structure manually or using editor warnings
✅ Week 10 (Node.js CRUD API - Express)
⚙️ Setup Project
Open terminal
npm init
npm install express
📄 Create Server
Create file: server.js
Paste Express CRUD code
🚀 Run Server
node server.js
🌐 Test API using Postman
Copy: http://localhost:PORT
🔍 API Testing
GET: /students
POST: /students
PUT: /students/:id
DELETE: /students/:id
✅ Week 11 (JWT Authentication API)
⚙️ Install Dependencies
npm init
npm install express
npm install jsonwebtoken
npm install bcryptjs
📄 Create Server
Create server.js
Paste authentication + login code
🚀 Run Server
node server.js
🔐 Login API Test (Postman)
Method: POST /login
Body → raw → JSON:
{
  "username": "admin",
  "password": "password123"
}
🔑 Token Usage
Copy JWT token from response
Go to Authorization tab
Select Bearer Token
Paste token
Access protected routes (same CRUD as Week 10)
✅ Week 12 (Frontend React App Setup)
📂 Open Project
Open terminal in folder
▶️ Run React App
npm install
npm run dev
Open browser:
http://localhost:5173
✅ Week 13 (React + Charts Project)
📁 Setup Project
cd WAD13
npm install
npm install chart.js react-chartjs-2
npm run dev
🌐 Run Project
Open:
http://localhost:5173
📊 Features
Charts will render using Chart.js
Data visualization in UI
✅ Week 14 (Final React Project Run)
🚀 Run Project
npm install
npm run dev
🌐 Open in Browser
http://localhost:5173