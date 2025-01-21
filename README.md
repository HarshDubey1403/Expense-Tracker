# Expense-Tracker

## Features

### Landing Page
- Welcoming and guiding users to sign up or log in using Google authentication.
- JWT token storage in cookies to ensure users don't need to re-authenticate every time.

### Dashboard

#### Stats Page
- Overview cards showing total budget amounts, total spending amounts, and the number of budgets.
- Pie chart displaying the latest five budgets with their total amounts and spent money.
- Latest budgets cards and a detailed table of the latest expenses.

#### Budget Page
- View all budgets with details including total amount, spending, emoji, and name.
- "View Detail" button to open a detailed page of the selected budget.
- Options to add, edit, or delete expenses and modify or delete the budget itself.
- Expenses displayed in an editable table.

#### Expenses Page
- Comprehensive table listing all expenses using the same table component as in the Stats and Budget pages.

## Technologies Used

- *MongoDB*: Database for storing user data, budgets, and expenses.
- *React*: Front-end library for building the user interface.
- *Express*: Back-end framework for handling server-side logic.
- *Node.js*: JavaScript runtime for server-side development.
- *Firebase*: Google authentication for secure login and signup.
- *TailwindCSS*: Utility-first CSS framework for styling the application.

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- Firebase account

### SetUp


### client env

- VITE_FIREBASE_API_KEY=FIREBASE_API_KEY
- VITE_API_URL=http://localhost:3000


### server env

- MONGO_URI=mongodb_connection_string
- SALT=16
- JWT_SECRET=secret_key
- CLIENT_URL=http://localhost:5173

### Deployment
- https://expense-tracker-frontend-beryl-chi.vercel.app/

### Client
-npm run dev

### Server
-node index.js
