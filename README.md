# 🎬 QuickShow – Movie Ticket Booking Platform

QuickShow is a **full-stack movie ticket booking web application** built using the **MERN stack**.  
It allows users to browse movies, check show timings, select seats, and book tickets securely with online payments.

This project demonstrates **modern full-stack development, authentication, API integration, and payment processing**.

---

# 🚀 Features

### 👤 User Features
- 🎥 Browse movies and view movie details
- ⏰ View available show timings
- 💺 Select seats and book tickets
- 💳 Secure online ticket payment
- 📜 View booking history
- 📱 Fully responsive user interface

### 🛠 Admin Features
- ➕ Add or manage movies
- 🎬 Manage show timings
- 📊 Monitor bookings

---

# 🧰 Tech Stack

### Frontend
- React  
- Tailwind CSS  
- Axios  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  

### Authentication
- Clerk  

### Payment Integration
- Stripe  

---

# 🏗 System Architecture

```
User (Browser)
      |
      v
React Frontend
      |
      v
Node.js + Express Backend
      |
      v
MongoDB Database
      |
      v
Stripe Payment Gateway
```

---

# 📂 Project Structure

```
QuickShow-FullStack
│
├── client
│   ├── src
│   ├── components
│   ├── pages
│   └── package.json
│
├── server
│   ├── controllers
│   ├── routes
│   ├── models
│   ├── middleware
│   └── server.js
│
├── .gitignore
├── README.md
└── package.json
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the repository

```bash
git clone https://github.com/VandanaSh178/QuickShow-Deploy1.git
cd QuickShow-FullStack
```

---

## 2️⃣ Install Dependencies

### Frontend

```bash
cd client
npm install
```

### Backend

```bash
cd ../server
npm install
```

---

## 3️⃣ Environment Variables

Create a `.env` file inside the **server** folder.

Example:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
STRIPE_SECRET_KEY=your_stripe_secret_key
CLERK_SECRET_KEY=your_clerk_secret_key
JWT_SECRET=your_jwt_secret
```

---

## 4️⃣ Run the Application

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

Frontend will run on:

```
http://localhost:3000
```

Backend will run on:

```
http://localhost:5000
```

---

# 🔌 API Endpoints

### Movies

```
GET  /api/movies
POST /api/movies
```

### Bookings

```
POST /api/bookings
GET  /api/bookings/user
```

---


# 🔒 Security

Sensitive credentials such as API keys and database connection strings are stored in **environment variables** using `.env` files and excluded from version control using `.gitignore`.

---

# 🚀 Future Improvements

- Real-time seat locking using Socket.IO  
- Email ticket confirmation  
- QR code ticket generation  
- Admin analytics dashboard  
- Movie recommendation system  
- Mobile app version

---

# 👩‍💻 Author

**Vandana Sharma**

GitHub  
https://github.com/VandanaSh178  

LinkedIn  
https://www.linkedin.com/in/vandana-sharma-2baba6205

---

# ⭐ Support

If you like this project, please consider **starring the repository ⭐** on GitHub to support the project.
