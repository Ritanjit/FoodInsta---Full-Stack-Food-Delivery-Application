# 🍴 FoodInsta — Full-Stack Food Delivery Application

A modern **Full-Stack Food Delivery Application** that provides an end-to-end food ordering experience. FoodInsta is built with a **scalable architecture** combining a responsive frontend, robust backend, and a structured database layer to simulate a real-world food delivery platform.

---

## 🚀 Features

- 🛒 **User-Friendly Ordering** — Browse, add to cart, and order meals effortlessly.
- 🔐 **Authentication System** — Secure login/signup for users & admins.
- 🍔 **Restaurant & Menu Management** — Admins can add/manage restaurants and food items.
- 💳 **Payment Integration** — Supports secure checkout with payment gateway.
- 📦 **Order Tracking** — Real-time order status and history.
- 📱 **Responsive UI** — Mobile-first design for seamless usage across devices.

---

## 🛠️ Tech Stack

### **Frontend:**
- React.js
- Redux Toolkit (state management)
- TailwindCSS (styling)

### **Backend:**
- Node.js
- Express.js

### **Database:**
- MongoDB (NoSQL Database)

### **Other Tools:**
- JWT Authentication
- RESTful APIs
- Axios

---

## 📂 Project Structure
```
FoodInsta---Full-Stack-Food-Delivery-Application/
│── backend/            # Express.js backend APIs
│── frontend/           # React.js frontend code
│── config/             # Configuration files
│── public/             # Static assets
│── package.json        # Project metadata & dependencies
│── README.md           # Documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Ritanjit/FoodInsta---Full-Stack-Food-Delivery-Application.git
cd FoodInsta---Full-Stack-Food-Delivery-Application
```

### 2️⃣ Install dependencies
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file inside **backend** folder and add:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PAYMENT_GATEWAY_KEY=your_payment_gateway_key
```

### 4️⃣ Run the Application
```bash
# Run backend
cd backend
npm start

# Run frontend
cd frontend
npm start
```

The application will run at:
- Frontend: `http://localhost:3000`
- Backend: `http://localhost:5000`

---

## 🖼️ UI Gallery

<table>
  <tr>
    <td align="center"><img src="./ui/login.png" width="300"><br><b>Login Page</b></td>
    <td align="center"><img src="./ui/signup.png" width="300"><br><b>Signup Page</b></td>
  </tr>
  <tr>
    <td align="center"><img src="./ui/home.png" width="300"><br><b>Home Page</b></td>
    <td align="center"><img src="./ui/restaurant-list.png" width="300"><br><b>Restaurant Listing</b></td>
  </tr>
  <tr>
    <td align="center"><img src="./ui/menu.png" width="300"><br><b>Menu Page</b></td>
    <td align="center"><img src="./ui/cart.png" width="300"><br><b>Shopping Cart</b></td>
  </tr>
  <tr>
    <td align="center"><img src="./ui/checkout.png" width="300"><br><b>Checkout Page</b></td>
    <td align="center"><img src="./ui/order-tracking.png" width="300"><br><b>Order Tracking</b></td>
  </tr>
</table>

---

## 📈 Future Enhancements

- 🔍 Advanced search & filters
- 🌍 Multi-language support
- 🛵 Real-time delivery tracking with maps
- 📊 Admin analytics dashboard

---

## 🤝 Contributing

Contributions are welcome! To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature-branch`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Ritanjit Das**  
📧 [ritanjitdas.dev@gmail.com](mailto:ritanjitdas.dev@gmail.com)  
🔗 [Portfolio](https://ritanjit.github.io) | [LinkedIn](https://www.linkedin.com/in/ritanjitdas/) | [GitHub](https://github.com/Ritanjit)
