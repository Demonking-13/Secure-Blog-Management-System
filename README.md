# 📝 Secure Blog Management System

A full-stack web application that allows authenticated users to create, read, update, and delete blog posts. This project is built with **React.js** for the frontend, **Node.js** and **Express.js** for the backend, and **MongoDB** as the database. The application supports private routing, session-based authentication, and responsive UI with Material-UI.

---

## 🚀 Features

- User authentication and session management
- Secure private routes for authenticated users
- Create, view, update, and delete blog posts
- Responsive and modern UI using Material-UI
- Dynamic routing with React Router
- Clean and modular code structure

---

## 🛠️ Tech Stack

**Frontend**  
- React.js  
- React Router  
- Material-UI  

**Backend**  
- Node.js  
- Express.js  
- MongoDB  
- dotenv, cors, body-parser  

---

## 📁 Project Structure

```

├── server/
│   ├── index.js
│   ├── database/
│   │   └── db.js
│   └── routes/
│       └── route.js
├── client/
│   ├── App.js
│   ├── components/
│   └── context/
└── README.md

```

---

## 🔧 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Demonking-13/Secure-Blog-management-app.git
cd blog-management-app
````

### 2. Set Up Backend

```bash
cd backend
npm install
```

Create a `.env` file and add:

```
DB_USERNAME=your_mongodb_username
DB_PASSWORD=your_mongodb_password
```

Start the server:

```bash
npm start
```

### 3. Set Up Frontend

```bash
cd ../frontend
npm install
npm start
```

The app will run on [http://localhost:3000](http://localhost:3000)

---

## ✅ Usage

1. Register or log in to the application.
2. Navigate through the dashboard to:

   * **Create** new blog posts.
   * **View** post details.
   * **Edit** existing posts.
   * **Delete** posts securely.
3. Only authenticated users can access protected routes.

---

## 🧪 Testing

* Use browser dev tools to test session storage and route access.
* Test APIs using Postman for various CRUD operations.
* Validate component rendering and conditional logic based on user authentication.

---

## 📈 Future Enhancements

* Role-based access control (Admin, Editor)
* Rich text editor for blog content
* Image and file upload support
* Comment system
* Deployment to cloud platforms (e.g., Render, Vercel, Heroku)

---

## 💡 Learnings

* Hands-on experience with full-stack development
* Securing routes and managing sessions in React
* Structuring backend with Express and MongoDB
* Importance of modular, scalable architecture

---

## 📚 References

* [React Documentation](https://reactjs.org/docs/getting-started.html)
* [Express Documentation](https://expressjs.com/)
* [MongoDB Documentation](https://docs.mongodb.com/)
* [Material-UI Docs](https://mui.com/)

---

## 👨‍💻 Author

**Devjit chowdhury**
📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/devjit-chowdhury-77bba3248/) | [GitHub](https://github.com/Demonking-13)

