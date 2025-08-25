Income-Expense Website

A Secure Income & Expense Tracker with Full Authentication and JWT Token

This repository contains the source code for an Income-Expense Website with full authentication and JWT token-based security.
The application allows users to securely track their income and expenses, manage transactions, and view summary statistics and charts.

Features

✅ User registration and login with JWT authentication
✅ Secure access to income and expense management
✅ Add, edit, and delete income and expense transactions
✅ Categorize income and expenses for better organization
✅ View summary statistics and charts to analyze financial trends


Prerequisites

Before you begin, make sure you have the following installed:
Node.js and npm
MongoDB (installed and running)
A text editor or IDE (e.g., VS Code)
Basic knowledge of JavaScript and web development

Installation
1. Clone the repository
```
   git clone https://github.com/yourusername/income-expense-website.git
```

2. Navigate to the project directory
```
cd income-expense-website
```

3. Install dependencies
```
npm install
```

4. Create a .env file
Inside the project root, create a .env file and configure the following variables:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/income-expense
JWT_SECRET=your-secret-key
```
🔹 Replace your-secret-key with a strong and unique secret key for JWT token generation.

5. Run the application
```
npm start
```
