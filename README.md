# 🌓 MoonKnight-Themed User Management System (UMS)

A secure, modular **User Management System** built with **Node.js**, **Express**, **MongoDB**, and **EJS**.  
This project marks my **first full-stack application**, implementing frontend + backend + authentication + database from scratch.

> 🎨 The UI is entirely designed with the help of ChatGPT, inspired by the **MoonKnight** aesthetic — sleek, dark, and mysterious.

🔗 **Live Link**: *(Add your deployed link here)*  
📦 **Stack**: Node.js | Express | MongoDB | EJS | HTML | CSS

---

## ✨ Features

- 🔐 **Secure Authentication**
  - Signup, Login, Logout
  - Passwords hashed with `bcrypt`
- 👤 **User Profile Management**
  - View/update name & email
  - Delete own account
- 🛡️ **Admin Panel**
  - View all users
  - Block, unblock, or delete users
- 🗃️ **MongoDB Integration**
  - Uses `mongoose` for schema modeling and CRUD operations
- 🌐 **EJS-Based UI**
  - Clean, dark-themed interface
  - Responsive and user-friendly templates
- 🧱 **Session Handling**
  - Login persistence using `express-session`
- ❌ **Robust Error Handling**
  - Graceful messages and route protection
- 🎨 **MoonKnight UI**
  - Subtle animations, smooth layout, sharp contrast  
  - Fully generated and polished with GPT's help

---

## 🗂️ Folder Structure

```
user-management-system/
├── config/          # MongoDB config file
├── controllers/     # Auth & User logic
├── middleware/      # Auth checks and error handling
├── models/          # User schema (Mongoose)
├── public/          # CSS, assets
├── routes/          # User & admin routes
├── views/           # EJS UI templates
├── index.js         # Main server entry point
├── package.json     # Project metadata
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/nashid-k/user-management-system.git
cd user-management-system
```

### 2. Install dependencies

```bash
npm install
```

### 3. Setup MongoDB

Update the MongoDB URI in `config/db.js`:

```javascript
mongoose.connect('mongodb://localhost:27017/ums-app', {
  useNewUrlParser: true,
  useUnifiedTopology: true,
});
```

Or use `.env` and `dotenv` for security (recommended in production)

### 4. Run the application

```bash
npm start
```

Then open your browser at: `http://localhost:3000`

---

## 🛠️ Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Template Engine**: EJS
- **Authentication**: bcrypt for password hashing
- **Session Management**: express-session
- **Frontend**: HTML5, CSS3, JavaScript

---

## 📝 Environment Variables

Create a `.env` file in the root directory:

```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/ums-app
SESSION_SECRET=your-secret-key-here
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **MoonKnight** for the design inspiration
- **ChatGPT** for UI design assistance
- **MongoDB** and **Express.js** communities for excellent documentation

---

## 📧 Contact

**Nashid K** - [nashidk1999@gmail.com](mailto:nashidk1999@gmail.com)

Project Link: [https://github.com/nashid-k/user-management-system](https://github.com/nashid-k/user-management-system)
