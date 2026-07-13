# Auth Service

Authentication and Authorization service built with Node.js and Express.

## Features

- User Registration
- User Login
- JWT Authentication
- Password Hashing with bcrypt
- Protected Routes
- Role-Based Access Control (RBAC)

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- dotenv

## Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/01-auth-service.git
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

## Environment Variables

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Project Structure

```
src/
├── config/
├── controllers/
├── middleware/
├── models/
├── routes/
├── services/
├── utils/
└── app.js
```

## License

MIT
