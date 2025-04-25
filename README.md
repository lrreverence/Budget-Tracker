# Budget Tracker

A full-stack web application for tracking income and expenses.

## Features

- User authentication (register/login)
- Add, edit, and delete transactions
- Track income and expenses
- View transaction history
- Calculate current balance
- Responsive design

## Tech Stack

- Frontend: React, Material-UI
- Backend: Node.js, Express
- Database: MongoDB
- Authentication: JWT

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd budget-tracker
```

2. Set up the backend:
```bash
cd server
npm install
```

3. Create a `.env` file in the server directory with the following variables:
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/budget-tracker
JWT_SECRET=your-secret-key-here
```

4. Set up the frontend:
```bash
cd ../client
npm install
```

5. Start MongoDB:
```bash
mongod
```

6. Start the backend server:
```bash
cd server
npm start
```

7. Start the frontend development server:
```bash
cd client
npm start
```

The application will be available at `http://localhost:3000`.

## Usage

1. Register a new account or login with existing credentials
2. Add transactions by clicking the "Add Transaction" button
3. View your transaction history and current balance
4. Edit or delete transactions as needed

## License

MIT 