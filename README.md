
# 🛒 ShopEZ

ShopEZ is a full-stack e-commerce web application built with the **MERN stack** (MongoDB, Express.js, React, Node.js). It features user authentication, product browsing, shopping cart, admin management, and more.


## ✨ Features

- 🔐 **User Authentication:** Register and log in as a customer or admin.
- 🛍️ **Product Catalog:** Browse products by category, view details, and add to cart.
- 🛒 **Shopping Cart:** Manage cart items and proceed to checkout.
- 🧑‍💼 **Admin Dashboard:** Manage products, users, and orders.
- ⚡ **Flash Sales & Promotions:** Highlighted deals on the homepage.
- 📱 **Responsive UI:** Built with React and Bootstrap for modern, mobile-friendly design.


## 🗂️ Project Structure

```
ShopEZ/
│
├── Project Files/
│   ├── client/         # React frontend
│   └── server/         # Express backend
│
├── README.md           # Project overview (this file)
└── ...
```


### 💻 Client

- ⚛️ Built with React
- 🧭 Uses React Router for navigation
- 🔗 Axios for API requests
- 🎨 Bootstrap for styling

**Run the client:**
```sh
cd "Project Files/client"
npm install
npm start
```

### 🖥️ Server

- 🚀 Built with Express.js
- 🍃 MongoDB for data storage (via Mongoose)
- 👥 Supports user, product, and order management
- 🔑 Uses dotenv for environment variables

**Run the server:**
```sh
cd "Project Files/server"
npm install
npm start
```


## ⚙️ Environment Variables

Create a `.env` file in the `server` directory with your MongoDB connection string:
```
MONGODB_URI=your_mongodb_connection_string
```


## 🛠️ Scripts

- `npm start` - Start the development server (client or server)
- `npm run build` - Build the React app for production (client)


## 🚀 Getting Started

1. 📥 Clone the repository
2. 📦 Install dependencies in both `client` and `server` folders
3. 📝 Set up your MongoDB connection string in the server's `.env` file
4. ▶️ Start both the client and server


## 📄 License

This project is licensed under the ISC License.