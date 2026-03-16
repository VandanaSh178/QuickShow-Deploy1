🎬 QuickShow – Movie Ticket Booking Platform

QuickShow is a full-stack movie ticket booking web application built using the MERN stack.
Users can browse movies, view show timings, select seats, and book tickets securely with online payments.

This project demonstrates modern full-stack development, authentication, API integration, and payment processing.

🚀 Features

✅ Browse movies and show details
✅ View available showtimes
✅ Select seats and book tickets
✅ Secure user authentication
✅ Online payments integration
✅ Responsive modern UI
✅ Admin dashboard for managing shows
✅ Booking history for users

🛠 Tech Stack
Frontend

React

Tailwind CSS

Axios

Backend

Node.js

Express.js

Database

MongoDB

Authentication

Clerk

Payment Integration

Stripe

📂 Project Structure
QuickShow-FullStack
│
├── client        # React frontend
│
├── server        # Node.js backend
│
├── .gitignore
├── package.json
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/VandanaSh178/QuickShow-Deploy1.git
cd QuickShow-FullStack
2️⃣ Install dependencies

Frontend:

cd client
npm install

Backend:

cd ../server
npm install
3️⃣ Create Environment Variables

Create a .env file inside the server folder.

Example:

PORT=5000
MONGO_URI=your_mongodb_connection
STRIPE_SECRET_KEY=your_stripe_key
CLERK_SECRET_KEY=your_clerk_key
JWT_SECRET=your_secret
4️⃣ Run the application

Start backend:

cd server
npm run dev

Start frontend:

cd client
npm start
🌐 API Endpoints
Movies
GET /api/movies
POST /api/movies
Bookings
POST /api/bookings
GET /api/bookings/user
📸 Screenshots

You can add screenshots like:

Home Page

Movie Details

Seat Selection

Booking Confirmation

Example:

![Home Page](screenshots/home.png)
🔒 Security

Environment variables are stored in .env files and excluded using .gitignore to protect sensitive data like API keys.

📈 Future Improvements

Real-time seat locking with Socket.IO

Email ticket confirmation

QR code tickets

Admin analytics dashboard

Movie recommendation system

👩‍💻 Author

Vandana Sharma

GitHub: https://github.com/VandanaSh178

LinkedIn: www.linkedin.com/in/vandana-sharma-2baba6205

⭐ Support

If you like this project, consider starring the repository on GitHub to support the work.
