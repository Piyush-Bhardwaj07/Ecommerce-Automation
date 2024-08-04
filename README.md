# Ecommerce-Automation
🌐 E-Commerce Automation Project
Welcome to the E-Commerce Automation Project! This project uses Playwright to automate a sample test e-commerce website, covering various user interactions such as signing up, logging in, logging out, searching for products, adding items to the cart, and deleting accounts.

🚀 Project Overview
This project demonstrates how to automate the following functionalities on a sample e-commerce website:

📝 Sign Up
🔐 Login
🚪 Logout
🔍 Search Products
🛒 Add to Cart
❌ Delete Account
🛠️ Installation and Setup
To get started with this project, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/ecommerce-automation.git
Navigate to the project directory:

bash
Copy code
cd ecommerce-automation
Install dependencies:

bash
Copy code
npm install
Run the tests:

bash
Copy code
npx playwright test
📁 Project Structure
Here's an overview of the project structure:

go
Copy code
ecommerce-automation/
│
├── tests/
│   ├── signup.spec.js
│   ├── login.spec.js
│   ├── logout.spec.js
│   ├── search.spec.js
│   ├── addToCart.spec.js
│   └── deleteAccount.spec.js
│
├── pages/
│   ├── signup.page.js
│   ├── login.page.js
│   ├── logout.page.js
│   ├── search.page.js
│   ├── addToCart.page.js
│   └── deleteAccount.page.js
│
├── utils/
│   └── helpers.js
│
├── .gitignore
├── package.json
└── README.md
🔍 Test Cases
📝 Sign Up
Test Case: Ensure a new user can sign up successfully.
File: tests/signup.spec.js
🔐 Login
Test Case: Verify that a registered user can log in.
File: tests/login.spec.js
🚪 Logout
Test Case: Check that a logged-in user can log out.
File: tests/logout.spec.js
🔍 Search Products
Test Case: Confirm that users can search for products using the search bar.
File: tests/search.spec.js
🛒 Add to Cart
Test Case: Verify that users can add products to their cart.
File: tests/addToCart.spec.js
❌ Delete Account
Test Case: Ensure that a user can delete their account.
File: tests/deleteAccount.spec.js
🧩 Utilities
helpers.js
Contains helper functions used across different test cases.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

