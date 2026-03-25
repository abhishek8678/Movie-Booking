# Movie Booking Application 🎬🍿

A full-stack web application for browsing movies and booking tickets seamlessly. This project features user authentication, a movie catalog, seat selection, and secure payment processing.

## 🚀 Features

- **User Authentication**: Secure sign-up and login functionality using JWT and bcrypt.
- **Movie Catalog**: Browse available movies and view their details.
- **Seat Booking**: Select seats for your favorite movies interactively.
- **Secure Payments**: Integrated with Stripe for handling ticket payments.
- **Ticket Generation**: Generates booking details and QR codes for digital tickets.
- **Responsive Design**: A beautiful, minimalist UI that works well on different screen sizes.

## 💻 Tech Stack

### Frontend
- **React 19** with **Vite**
- **TailwindCSS v4** for styling
- **React Router v7** for navigation
- **Axios** for API requests
- **Lucide React** for icons
- **QR Code** rendering for tickets

### Backend
- **Node.js** with **Express**
- **MongoDB** with **Mongoose** for the database
- **JWT** & **Bcrypt** for authentication
- **Stripe** API for payment gateway
- **Multer** for file uploads
- **Dotenv** for environment variable management

## 🛠️ Installation & Setup

### Prerequisites
- [Node.js](https://nodejs.org/) installed
- [MongoDB](https://www.mongodb.com/) running locally or a MongoDB Atlas connection string
- A [Stripe](https://stripe.com/) account for payment processing

### 1. Clone the repository

```bash
git clone https://github.com/abhishek8678/Movie-Booking.git
cd Movie-Booking
```

### 2. Setup the Backend

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory and add your secret keys:
```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Start the backend development server:
```bash
npm start
```

### 3. Setup the Frontend

Open a new terminal and navigate to the frontend folder:
```bash
cd frontend
npm install
```

Start the frontend Vite development server:
```bash
npm run dev
```

The application will now be running at `http://localhost:5173/`.

---
> Developed by **Abhishek Kumar** (`abhishek8678`)
