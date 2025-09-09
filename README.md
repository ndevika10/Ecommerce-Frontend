# 🛍️ E-commerce Frontend

This repository contains the **frontend** for a modern, responsive e-commerce web application.  
It is built using **React**, **Vite**, and **Tailwind CSS**, featuring both customer-facing pages and an admin dashboard.

---

## 🚀 Features

### Customer Features
- Browse products by categories (Men, Women, Saree, Kurta, etc.)
- Add products to cart
- Checkout functionality
- User authentication (Sign Up, Login)
- Responsive design optimized for desktop and mobile

### Admin Features
- Dashboard with analytics and KPIs
- Manage products (Create, View, Update)
- Manage orders and customers
- Monthly overview and achievements

### State Management
- Redux-based architecture (`src/State/`)
- Separate actions and reducers for:
  - Authentication
  - Cart
  - Orders
  - Products

---

## 🛠️ Tech Stack

- **Frontend Framework:** React (with JSX)
- **Build Tool:** Vite
- **Styling:** Tailwind CSS, Custom CSS
- **State Management:** Redux
- **Routing:** React Router
- **Deployment Ready:** Configured for Vercel / Netlify (`vercel.json` included)

---

## 📂 Project Structure
src/
├── Admin/ # Admin dashboard pages and components
│ └── components/ # Modular dashboard widgets (tables, forms, etc.)
├── Data/ # Static product data (JSON & JS)
├── Routers/ # Routing configuration for Admin & Customer
├── State/ # Redux actions, reducers, store
├── App.jsx # Main application component
├── main.jsx # React DOM entry point
└── index.css # Global styles


---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>


Install dependencies:

npm install


Run the development server:

npm run dev


Open in your browser:

http://localhost:5173

🌐 API Integration

This frontend communicates with a backend API for:

User authentication

Product listing and details

Cart and order management

Note: Update the API base URL in the configuration (if applicable).

🧪 Testing

Run available tests (if configured):

npm test

📦 Deployment

Optimized for Vercel or Netlify.

To create a production build:

npm run build


The dist folder will contain the optimized production-ready code.

👥 Contributing

Contributions are welcome!
Please fork the repository and create a pull request for any feature or bug fix.

📄 License

This project is licensed under the MIT License.
