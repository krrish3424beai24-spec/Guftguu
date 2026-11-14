# Guftguu
> A modern social media app with **users, posts, likes, and comments**, built with **React, Node.js, Express, and MongoDB**.

---

## ⚡ Features

- 👤 **User Authentication** (JWT & hashed passwords)  
- 📝 **Posts & Comments** with likes  
- 🌐 **Responsive UI** (React & Material UI)  
- 🚀 **Backend with Node.js & Express**  
- 🗄 **Database:** MongoDB  
- 🔄 **Real-time updates & Social Feed**  

---

## 🛠 Prerequisites

- Node.js >= 13.12.0  
- NPM or Yarn  
- MongoDB (local or MongoDB Atlas)  

---

## 💻 Installation

```bash
# Install dependencies
npm install   # or yarn

# Start the development server
npm run development   # or yarn development
```

## ⚙️ Configuration

Environment variables can be customized in `config/config.js` or via environment variables:

- `PORT`: Server port (default: `3000`)
- `MONGODB_URI`: MongoDB connection string (default: `mongodb://localhost:27017/guftguu`)
- `JWT_SECRET`: Secret key for JWT authentication
