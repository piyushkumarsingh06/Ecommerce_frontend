🛒 E-Commerce Frontend
This is the frontend of a full-stack E-Commerce website built using React.js and Redux Toolkit. It allows users to register, log in, browse and filter products, manage their shopping cart, and securely complete purchases using Stripe.

🚀 Features
👤 User Registration & JWT Login

🛍️ Browse All Products

🧺 Add to Cart / Remove from Cart

🔍 Product Filtering by Category

💳 Stripe Payment Integration

🔐 Protected Routes using JWT

⚙️ API Integration with Spring Boot Backend

🧰 Tech Stack
React.js

Redux Toolkit (for global state management)

React Router DOM (for navigation)

Axios (for API requests)

Stripe JS (for payment processing)

Tailwind CSS / Bootstrap (choose based on your usage)

📂 Folder Structure
cpp
Copy
Edit
frontend/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   ├── App.js
│   ├── index.js
│   └── ...
🛠️ Setup Instructions
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/your-username/ecommerce-frontend.git
cd ecommerce-frontend
2. Install Dependencies
bash
Copy
Edit
npm install
3. Configure Backend API URL
Create a .env file in the root:

bash
Copy
Edit
REACT_APP_API_BASE_URL=http://localhost:8080/api
4. Run the Frontend
bash
Copy
Edit
npm start
The app will run at: http://localhost:3000

