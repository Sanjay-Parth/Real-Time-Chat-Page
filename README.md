# 💬 Talk-A-Tive

Talk-A-Tive is a **Full Stack Real-Time Chatting Application** built with the MERN stack. It uses **Socket.io** for instant, bi-directional messaging and stores user details in an **encrypted format** in a MongoDB database for enhanced security.

---


![Uploading image.png…]()




## ✨ Features

- 🔴 **Real-time messaging** — instant message delivery powered by Socket.io
- 🔐 **Encrypted user data** — sensitive user details are securely stored in MongoDB
- 👤 **User authentication** — register and log in securely
- 💬 **One-to-one & group chats**
- 📱 **Responsive UI** built with React JS
- ⚡ **Fast and lightweight** client-server architecture

---

## 🛠️ Tech Stack

| Layer        | Technology              |
|--------------|--------------------------|
| **Client**   | React JS                 |
| **Server**   | Node JS, Express JS      |
| **Database** | MongoDB                  |
| **Real-time**| Socket.io                |

---

## 📂 Project Structure

```
mern-chat-app/
├── frontend/        # React frontend
│   ├── public/
│   └── src/
├── backend (root)/  # Node + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── config/
└── README.md
```

---

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/talk-a-tive.git
```

### 2. Go to the project directory

```bash
cd mern-chat-app
```

### 3. Install backend dependencies

```bash
npm install
```

### 4. Install frontend dependencies

```bash
cd frontend/
npm install
```

### 5. Environment Variables

Create a `.env` file in the root directory and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 6. Start the server

From the root directory:

```bash
npm run start
```

### 7. Start the client

Open a new terminal:

```bash
cd frontend
npm start
```

The app will be available at `http://localhost:3000`, with the backend running on `http://localhost:5000`.

---

## ⚙️ Configuration

| Environment Variable | Description                  | Required |
|-----------------------|-------------------------------|----------|
| `PORT`                | Server port (default: 5000)  | No       |
| `MONGO_URI`           | MongoDB connection string    | Yes      |
| `JWT_SECRET`          | Secret key for JWT auth      | Yes      |

---

## 📈 Future Improvements

- 📎 File and image sharing in chats
- ✅ Message read receipts
- ✍️ Typing indicators
- 🔔 Push notifications
- 🌐 Deployment on Vercel / Render

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and open a pull request.

```bash
git checkout -b feature/your-feature-name
git commit -m "feat: add your feature"
git push origin feature/your-feature-name
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sanjay Kushwaha**
Full Stack Developer | MERN Stack Developer

⭐ If you found this project useful, consider giving it a star on GitHub!
