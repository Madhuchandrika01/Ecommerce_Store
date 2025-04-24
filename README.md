# 🛍️ E-Commerce Store - Urban

A full-stack e-commerce web application built with the **MERN stack**. This project provides a complete user and admin experience—from browsing and cart management to product administration and real-time analytics.

🔗 **Live Demo**: [Urban E-Commerce Store](https://projects-production-204f.up.railway.app/)

---

## ✨ Key Features

- 🔐 Secure JWT authentication for users and admins
- 🛒 Cart functionality with dynamic item updates
- 📦 Admin panel for managing products
- 📊 Revenue & sales analytics dashboard
- 💳 Stripe checkout integration
- ⚙️ Zustand-based global state management
- 🌐 Fully responsive design (Tailwind CSS)
- 🚀 Deployed on Railway

---

## 🧰 Tech Stack

**Frontend**  
- React.js  
- Zustand  
- Tailwind CSS  

**Backend**  
- Node.js  
- Express.js  
- MongoDB  
- Redis  

**Utilities & Services**  
- Stripe API (Payment processing)  
- JWT (Authentication)  
- Railway (Deployment)

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Madhuchandrika01/E-Commerce-Store.git
cd E-Commerce-Store
```

### 2. Backend Setup

```bash
cd backend
npm install
```

### 3. Environment Variables

Create a `.env` file in the `backend/` directory and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
REDIS_URL=your_redis_connection_url
```

### 4. Start the Backend

```bash
npm run dev
```

### 5. Frontend Setup

In a new terminal:

```bash
cd frontend
npm install
npm start
```

Visit: [http://localhost:3000](http://localhost:3000)

