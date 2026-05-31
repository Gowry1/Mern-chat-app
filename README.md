# MERN Chat Application

A full-stack real-time chat application built with **MongoDB**, **Express.js**, **React.js**, and **Node.js**. This project demonstrates modern web development practices, responsive design, and real-time communication capabilities.

---

## 🎯 Project Overview

This is a feature-rich chat application that allows users to communicate in real-time with an intuitive user interface and robust backend architecture. The application is designed for scalability, performance, and user experience.

---

## 🚀 Key Features

- ✅ **Real-time Messaging** – Instant message delivery using WebSocket technology
- ✅ **User Authentication** – Secure login and registration system
- ✅ **User Search** – Find and connect with other users
- ✅ **Conversation Management** – Create, manage, and organize multiple conversations
- ✅ **Responsive Design** – Works seamlessly on desktop, tablet, and mobile devices
- ✅ **Message Status** – View message delivery and read receipts
- ✅ **Online Status** – See who's available for chat
- ✅ **Profile Management** – Update user profile and avatar

---

## 🛠️ Tech Stack

### Frontend
- **React.js** – UI library for building interactive user interfaces
- **CSS3** – Advanced styling and responsive design
- **Socket.IO Client** – Real-time bidirectional communication
- **Axios** – HTTP client for API requests

### Backend
- **Node.js** – JavaScript runtime for server-side execution
- **Express.js** – Minimal web application framework
- **Socket.IO** – Real-time event-based communication
- **MongoDB** – NoSQL database for data persistence
- **JWT** – JSON Web Tokens for secure authentication

### Tools & Technologies
- **Git** – Version control system
- **npm** – Package manager
- **RESTful API** – Standard API architecture

---

## 📊 Code Composition

| Language | Percentage |
|----------|-----------|
| JavaScript | 97.1% |
| CSS | 2.1% |
| HTML | 0.8% |

---

## 📋 Prerequisites

Before running this project, ensure you have the following installed:

- **Node.js** (v14.0.0 or higher)
- **npm** (v6.0.0 or higher)
- **MongoDB** (local or MongoDB Atlas account)
- **Git**

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Gowry1/Mern-chat-app.git
cd Mern-chat-app
```

### 2. Backend Setup
```bash
cd backend
npm install
```

Create a `.env` file in the backend directory with the following variables:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NODE_ENV=development
```

Start the backend server:
```bash
npm start
```

The server will run on `http://localhost:5000`

### 3. Frontend Setup
```bash
cd frontend
npm install
```

Create a `.env` file in the frontend directory:
```env
REACT_APP_API_URL=http://localhost:5000
```

Start the React development server:
```bash
npm start
```

The application will open at `http://localhost:3000`

---

## 🗂️ Project Structure

```
Mern-chat-app/
├── backend/
│   ├── models/              # MongoDB schemas
│   ├── routes/              # API endpoints
│   ├── controllers/         # Business logic
│   ├── middleware/          # Authentication & validation
│   ├── server.js            # Express server setup
│   └── .env                 # Environment variables
│
├── frontend/
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── pages/           # Page components
│   │   ├── context/         # Context API for state management
│   │   ├── utils/           # Utility functions
│   │   ├── App.js
│   │   └── index.js
│   └── public/
│
└── README.md
```

---

## 🔐 API Endpoints

### Authentication
- `POST /api/auth/register` – User registration
- `POST /api/auth/login` – User login
- `POST /api/auth/logout` – User logout

### Users
- `GET /api/users` – Get all users
- `GET /api/users/:id` – Get user by ID
- `PUT /api/users/:id` – Update user profile
- `GET /api/users/search/:query` – Search users

### Messages
- `POST /api/messages` – Send a message
- `GET /api/messages/:conversationId` – Get messages for a conversation
- `DELETE /api/messages/:id` – Delete a message

### Conversations
- `POST /api/conversations` – Create a new conversation
- `GET /api/conversations` – Get all user conversations
- `DELETE /api/conversations/:id` – Delete a conversation

---

## 📱 Usage

1. **Register/Login** – Create an account or log in with existing credentials
2. **Search Users** – Use the search feature to find other users
3. **Start Chat** – Click on a user to start a conversation
4. **Send Messages** – Type and send messages in real-time
5. **Manage Conversations** – View all active conversations and switch between them

---

## 🎓 Key Concepts Demonstrated

- **RESTful API Design** – Clean and organized API structure
- **Real-time Communication** – WebSocket implementation with Socket.IO
- **Authentication & Authorization** – JWT-based secure authentication
- **Database Design** – Efficient MongoDB schema design
- **State Management** – React Context API or Redux implementation
- **Error Handling** – Comprehensive error handling on both frontend and backend
- **Responsive Web Design** – Mobile-first approach with CSS media queries
- **Security Best Practices** – Password hashing, CORS, environment variables

---

## 🚀 Future Enhancements

- [ ] Group chat functionality
- [ ] Message encryption for enhanced security
- [ ] Media file sharing (images, videos)
- [ ] Message search and filtering
- [ ] User notifications
- [ ] Typing indicators
- [ ] Message reactions and emoji support
- [ ] Dark mode theme
- [ ] Voice/Video calling integration

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 👨‍💻 Author

**Gowry1**  
GitHub: [@Gowry1](https://github.com/Gowry1)

---

## 📧 Contact & Support

For questions, feedback, or support:
- Open an issue on GitHub
- Contact me via GitHub profile

---

## 🙏 Acknowledgments

- React.js documentation
- MongoDB documentation
- Express.js community
- Socket.IO real-time communication library
- All open-source contributors

---

**⭐ If this project helped you, please consider giving it a star on GitHub!**
