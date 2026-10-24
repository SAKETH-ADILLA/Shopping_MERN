
# 🛒 Shopping MERN - Shopping Cart Web Application

A full-stack shopping cart application built using the MERN stack. The application allows users to browse products, manage cart items, update quantities, and store data using a backend API.

## 🚀 Features

- Browse 20+ products
- Add products to the shopping cart
- Update product quantities
- Remove products from the cart
- Manage cart items
- MongoDB data storage
- RESTful APIs for product and cart operations
- React-based frontend built with Vite

## 🛠️ Tech Stack

- **Frontend:** React.js, Vite
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **API:** REST APIs

## 📂 Project Structure

```text
Shopping_MERN/
├── client/
│   ├── public/
│   ├── src/
│   ├── index.html
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   └── package.json
│
└── README.md
```

## ⚙️ Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB or MongoDB Atlas
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/SAKETH-ADILLA/Shopping_MERN.git
cd Shopping_MERN
```

### 2. Start the Backend

```bash
cd server
npm install
```

Configure your environment variables in a `.env` file using the variable names expected by your backend configuration.

Start the backend using the script defined in `server/package.json`, for example:

```bash
npm start
```

### 3. Start the Frontend

Open a new terminal:

```bash
cd client
npm install
npm run dev
```

Open the local URL displayed by Vite in your browser.

## 🔌 API Functionality

The backend provides API functionality for product and shopping cart operations, including:

- Retrieving products
- Adding items to the cart
- Updating item quantities
- Removing items from the cart

Refer to the `server/routes` directory for the actual API endpoints.

## 💡 Key Learnings

- Building REST APIs with Node.js and Express.js
- Connecting MongoDB with a backend application
- Integrating React with backend services
- Managing shopping cart operations
- Organizing backend code using routes, controllers, models, and middleware

## 🔮 Future Improvements

- User authentication and authorization
- Product search and filtering
- Checkout and payment integration
- Order history
- Unit and integration testing

## 👨‍💻 Author

**Saketh Adilla**

- GitHub: [SAKETH-ADILLA](https://github.com/SAKETH-ADILLA)
- Repository: [Shopping_MERN](https://github.com/SAKETH-ADILLA/Shopping_MERN)

---

⭐ If you find this project useful, consider giving the repository a star!
