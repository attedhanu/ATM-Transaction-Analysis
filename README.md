💳 ATM Transaction Analysis & Payment Dashboard
📌 Project Overview

ATM Transaction Analysis & Payment Dashboard is a Flask-based web application developed using Python, Pandas, HTML, CSS, and CSV files. The application provides a dashboard for analyzing ATM transaction data and also includes basic digital payment features such as account creation, money transfer, and payment history.

The project is designed as an educational/demo application to understand web development, data analysis, transaction management, and Flask-based application development.

🎯 Objectives
Analyze ATM transaction data.
Display transaction statistics through a dashboard.
Search and view ATM transactions.
Provide transaction analytics.
Create user accounts with different account types.
Simulate money transfers using UPI.
Maintain payment history.
Store application data using CSV files.
✨ Features
📊 Dashboard
Total transactions
Total transaction amount
Average transaction amount
Debit transactions
Credit transactions
Suspicious login attempts
Channel analysis
Transaction type analysis
Location analysis
Customer occupation analysis
👤 Create Account

Users can create an account by entering:

Name
Mobile Number
Email
UPI ID
Account Type
4-digit PIN

Available account types:

Savings Account
Current Account
Salary Account
Student Account
Business Account

Account information is automatically stored in accounts.csv.

💰 Send Money

Users can:

Select account type
Enter receiver UPI ID
Enter payment amount
Add description
Select payment method
Complete a simulated payment

Available payment methods:

UPI
ATM
Card
Bank Transfer

Payment information is stored in payments.csv.

📜 Payment History

Users can view:

Account Type
Receiver UPI ID
Amount
Description
Payment Method
Date and Time
💳 ATM Transactions

The application displays transaction records from the ATM dataset and provides a search option.

📈 Analytics

The analytics page provides analysis based on:

Transaction Channel
Transaction Type
Customer Occupation
Location
Login Attempts
🛠️ Technologies Used
Python
Flask
Pandas
HTML5
CSS3
Jinja2
CSV
📂 Dataset

The ATM transaction dataset contains information such as:

TransactionID
AccountID
TransactionAmount
TransactionDate
TransactionType
Location
DeviceID
IP Address
MerchantID
Channel
CustomerAge
CustomerOccupation
TransactionDuration
LoginAttempts
AccountBalance
PreviousTransactionDate
📁 Project Structure
Dae project/
│
├── app.py
├── atm_transactions.csv
├── accounts.csv
├── payments.csv
│
├── static/
│   └── style.css
│
└── templates/
    ├── index.html
    ├── create_account.html
    ├── account_created.html
    ├── send_money.html
    ├── payment_success.html
    ├── payment_history.html
    ├── transactions.html
    └── analytics.html
⚙️ Installation & Setup
1. Clone the repository
git clone YOUR_GITHUB_REPOSITORY_LINK
2. Open the project folder
cd "Dae project"
3. Install required packages
pip install flask pandas
4. Run the Flask application
python app.py
5. Open the application

Open your browser and visit:

http://127.0.0.1:5000/
🌐 Application Routes
/                    → Dashboard
/create-account      → Create Account
/send-money          → Send Money
/payment-history     → Payment History
/transactions        → ATM Transactions
/analytics           → Analytics
🔄 Application Workflow
Start Application
       ↓
Dashboard
       ↓
Create Account
       ↓
Account Details Saved
       ↓
Send Money
       ↓
Enter Receiver UPI
       ↓
Enter Amount & Payment Details
       ↓
Payment Recorded
       ↓
Payment Success
       ↓
Payment History
📊 Data Flow
ATM Dataset
     ↓
Pandas
     ↓
Data Processing
     ↓
Flask
     ↓
Web Dashboard
     ↓
Analytics & Transactions

For account and payment features:

User
 ↓
Create Account
 ↓
accounts.csv

User
 ↓
Send Money
 ↓
payments.csv
 ↓
Payment History
🔐 Security Note

This project is intended for learning and demonstration purposes. It does not connect to a real bank, UPI service, or payment gateway. The payment system only records simulated transactions in local CSV files.

🚀 Future Enhancements
Add user login and logout.
Add database support using MySQL/SQLite.
Add real-time transaction monitoring.
Add advanced charts and visualizations.
Add transaction filtering by date and amount.
Add fraud detection.
Add authentication and secure password/PIN handling.
Deploy the application online.
👩‍💻 Author

Anuradha(TL)
Ramya Sri
Sowmya Sri
Sudeepthi
CSE Student | Backend Developer

Skills: Python • C • Flask • Pandas • SQL • Data Analysis

📜 License

This project is created for educational and academic purposes
