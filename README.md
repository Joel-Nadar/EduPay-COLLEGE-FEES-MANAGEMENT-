🏫 EduPay - Smart School Fee Management System
EduPay is a full-stack web application designed to modernize school fee collection. It features a secure Student Portal for payments and a data-driven Admin Dashboard with real-time financial analytics.

🚀 Key Features
For Students
Secure Authentication: Dedicated login/signup for students using official college emails.

Fee Breakdown: Categorized view of Yearly, Term-wise, and Monthly dues.

Instant Receipts: Automated PDF receipt generation upon successful payment.

Payment History: A clean log of all past transactions.

For Administrators
Financial Intelligence: Live Chart.js integration showing Revenue Health (Donut Chart) and Departmental Collections (Bar Chart).

Advanced Filtering: Filter student records by Payment Status (Paid/Unpaid/Partial) and Department.

Student Management: Full CRUD capabilities to manage or remove student accounts.

🛠️ Tech Stack
Frontend: HTML5, Tailwind CSS, JavaScript (AJAX/Fetch API), Chart.js, Lucide Icons.

Backend: Python, Flask Framework.

Database: SQL (Relational Database Management).

Tools: ReportLab (PDF Generation), IO/Buffer management.

📁 Project Structure
Plaintext
├── app.py              # Main Flask Application
├── db.py               # Database connection logic
├── templates/          # HTML files (Index, Dashboards, Login/Signup)
├── static/             # CSS and JavaScript logic
└── requirements.txt    # Python dependencies

Run the application:

Bash
python app.py
Open http://127.0.0.1:5000 in your browser.

🛡️ License
This project is open-source and available under the MIT License.
