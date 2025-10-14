# 🎨 StyleForge - Visual Product Discovery

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![Node](https://img.shields.io/badge/Node.js-16+-339933?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-6.0-47A248?logo=mongodb)

> **AI-Powered Visual Search Engine for E-Commerce Products**

Upload any product image and instantly discover similar items across 6 categories with 120+ products. Built with React, Node.js, and MongoDB.

---

## ✨ Features

- 🖼️ **Image Upload & Search** - Find products by uploading images
- 🎯 **Smart Matching** - AI-powered similarity scoring (75-98%)
- 🏷️ **6 Categories** - Fashion, Electronics, Home & Living, Beauty, Sports, Books
- 📦 **120+ Products** - Extensive mock product database
- 🎨 **Beautiful UI** - Gradient designs with Framer Motion animations
- 📊 **Match Analytics** - Color, pattern, texture, and style analysis
- 📱 **Fully Responsive** - Works on all devices

---

## 🛠️ Tech Stack

### Frontend
- ⚛️ React 18 + Vite
- 🎨 Tailwind CSS
- 🌊 Framer Motion
- 🔥 React Hot Toast
- 📡 Axios

### Backend
- 🟢 Node.js + Express
- 🍃 MongoDB + Mongoose
- 📤 Multer (File Uploads)
- 🔒 CORS

---

## 🚀 Quick Start

### Prerequisites
\\\ash
node -v  # v16 or higher
npm -v   # v8 or higher
mongod --version  # MongoDB 6.0+
\\\

### Installation

1. **Clone the repository**
\\\ash
git clone https://github.com/NishantSharma07/StyleForge-Visual-Product-Matcher.git
cd StyleForge-Visual-Product-Matcher
\\\

2. **Install dependencies**
\\\ash
# Server dependencies
cd server
npm install

# Client dependencies
cd ../client
npm install
\\\

3. **Environment setup**

Create \.env\ in \/server\:
\\\env
PORT=5000
MONGODB_URI=mongodb://localhost:27017/styleforge
NODE_ENV=development
\\\

4. **Start MongoDB**
\\\ash
mongod
\\\

5. **Seed database** (Optional)
\\\ash
cd server
npm run seed
\\\

6. **Run the application**

**Terminal 1 - Backend:**
\\\ash
cd server
npm run dev
\\\

**Terminal 2 - Frontend:**
\\\ash
cd client
npm run dev
\\\

7. **Open browser**
- Frontend: http://localhost:5173
- Backend API: http://localhost:5000

---

## 📂 Project Structure

\\\
StyleForge-Visual-Product-Matcher/
├── client/                  # React Frontend
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── services/      # API services
│   │   ├── store/         # Zustand state management
│   │   └── App.jsx        # Main app
│   └── package.json
│
├── server/                 # Node.js Backend
│   ├── src/
│   │   ├── config/        # Database config
│   │   ├── data/          # Mock products (120 items)
│   │   ├── models/        # MongoDB schemas
│   │   ├── routes/        # API endpoints
│   │   └── server.js      # Entry point
│   └── package.json
│
├── .gitignore
└── README.md
\\\

---

## 🎯 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | \/api/categories\ | Get all categories |
| POST | \/api/match/upload\ | Upload image & get matches |
| POST | \/api/analytics/click\ | Track product clicks |

---

## 📸 Screenshots

### Home Page
![Home Page](https://via.placeholder.com/800x400/667eea/ffffff?text=Home+Page)

### Search Results
![Search Results](https://via.placeholder.com/800x400/764ba2/ffffff?text=Search+Results)

---

## 🔮 Roadmap

- [ ] Real AI image recognition (TensorFlow.js)
- [ ] User authentication & profiles
- [ ] Shopping cart & wishlist
- [ ] Product reviews & ratings
- [ ] Advanced filtering options
- [ ] Cloud deployment (Vercel + Railway)

---

## 👨‍💻 Developer

**Nishant Sharma**

[![GitHub](https://img.shields.io/badge/GitHub-NishantSharma07-181717?logo=github)](https://github.com/NishantSharma07)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nishant_Sharma-0077B5?logo=linkedin)](https://www.linkedin.com/in/-nishant-sharma-/)
[![Email](https://img.shields.io/badge/Email-nishantsharma232004%40gmail.com-D14836?logo=gmail)](mailto:nishantsharma232004@gmail.com)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Unsplash](https://unsplash.com) - Product images
- [Lucide React](https://lucide.dev) - Icons
- [Framer Motion](https://www.framer.com/motion/) - Animations

---

<div align='center'>
  <p>Made with ❤️ by Nishant Sharma</p>
  <p>⭐ Star this repo if you find it helpful!</p>
</div>
