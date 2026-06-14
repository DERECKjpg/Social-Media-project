# SocialSphere - MERN Stack Social Media Platform

A full-stack social media application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The platform allows users to create accounts, share posts, interact through likes and comments, follow other users, and receive real-time updates.

---

## 🚀 Features

### Authentication & Security
- User Registration
- User Login
- JWT Authentication
- Password Encryption using bcrypt
- Forgot Password Functionality
- Protected Routes
- Authorization Middleware
- Axios Interceptors for Secure Requests

### User Management
- User Profile Creation
- Profile Update
- Profile Picture Upload
- Public Profile View
- Find People Feature
- Follow / Unfollow Users
- Followers & Following List

### Posts Management
- Create Posts
- Edit Posts
- Delete Posts
- View Single Post
- Public Post Sharing
- Post Pagination
- Search Posts

### Social Interaction
- Like / Unlike Posts
- Add Comments
- Delete Comments
- View All Comments
- Real-time Post Updates
- User Activity Feed

### Real-Time Features
- Socket.IO Integration
- Live Broadcasting Events
- Real-Time Posts Updates

### Admin Features
- Admin Route Protection
- User Monitoring
- Content Management

### UI Features
- Responsive Design
- Ant Design Components
- Toast Notifications
- Dropdown Menus
- Modal Dialogs
- Dynamic Navigation
- SEO Optimization

---

# 🛠 Tech Stack

## Frontend
- React.js
- React Router
- Axios
- Ant Design
- Context API
- Socket.IO Client

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js
- Socket.IO

## Database
- MongoDB Atlas / MongoDB Local

---

# 📂 Project Structure

```
project-root/
│
├── client/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── routes/
│   └── api/
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── validators/
│   └── socket/
│
└── README.md
```

---

# 🔑 Main Modules

### Authentication Module
- Register User
- Login User
- Logout User
- Verify JWT Token
- Forgot Password

### User Module
- Profile Management
- User Search
- Follow/Unfollow System

### Post Module
- Create Post
- Update Post
- Delete Post
- View Posts

### Comment Module
- Add Comment
- Display Comments
- Delete Comment

### Like Module
- Like Post
- Unlike Post

### Real-Time Module
- Socket.IO Server
- Live Updates
- Broadcasting Events

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/socialsphere.git
```

```bash
cd socialsphere
```

---

## Install Backend Dependencies

```bash
cd server
npm install
```

---

## Install Frontend Dependencies

```bash
cd client
npm install
```

---

# 🔐 Environment Variables

Create a `.env` file inside the server directory:

```env
PORT=8000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

CLIENT_URL=http://localhost:3000

EMAIL_USER=your_email
EMAIL_PASS=your_password
```

---

# ▶ Running the Project

### Start Backend

```bash
cd server
npm run dev
```

---

### Start Frontend

```bash
cd client
npm start
```

---

# 🌐 Application Flow

1. User Registers
2. Password is encrypted using bcrypt
3. JWT Token is generated after login
4. Protected routes verify user identity
5. User can:
   - Create posts
   - Like posts
   - Comment on posts
   - Follow users
6. Socket.IO broadcasts updates in real-time

---

# 🔒 Security Features

- Password Hashing (bcrypt)
- JWT Authentication
- Route Protection
- Authorization Middleware
- Input Validation
- Environment Variable Protection
- Secure API Communication

---

# 📸 Screenshots

Add screenshots here:

### Login Page

![Login](screenshots/login.png)

### Register Page

![Register](screenshots/register.png)

### News Feed

![Feed](screenshots/feed.png)

### Profile Page

![Profile](screenshots/profile.png)

---

# 📈 Future Enhancements

- Chat System
- Story Feature
- Video Posts
- Notifications System
- Dark Mode
- Mobile Application
- AI Content Recommendations

---

# 👨‍💻 Developed By

**Gandharv Sood**

B.Tech Computer Science Engineering

---

# 📄 License

This project is developed for educational and learning purposes.

MIT License

---

⭐ If you found this project useful, don't forget to star the repository.
