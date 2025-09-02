# TrackMyFunds

A full-stack personal finance dashboard built with React, Vite, Express, and MongoDB. Track your income, expenses, savings goals, and visualize your financial data.

## Features

- User authentication (JWT)
- Add, view, and delete transactions
- Upload CSV bank statements
- Set and track savings goals
- Interactive charts (income/expense trends, expense breakdown)
- Responsive dashboard UI

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, Axios, Recharts
- **Backend:** Express, MongoDB, Mongoose, JWT, bcryptjs
- **Deployment:** Vercel

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB database

### Setup

#### 1. Clone the repository

```sh
git clone https://github.com/yourusername/TrackMyFunds.git
cd TrackMyFunds
```

#### 2. Install dependencies

```sh
cd client
npm install
cd ../server
npm install
```

#### 3. Configure environment variables

Create a `.env` file in `server/`:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

#### 4. Run the development servers

**Backend:**

```sh
cd server
node server.js
```

**Frontend:**

```sh
cd client
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

## Folder Structure

- `client/` - React frontend
- `server/` - Express backend

## API Endpoints

- `/api/auth/register` - Register user
- `/api/auth/login` - Login user
- `/api/auth/me` - Get current user
- `/api/transactions` - CRUD for transactions
- `/api/goals` - CRUD for savings goals

## License

MIT

---

Made with ❤️ by VivekChouhan
