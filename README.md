![Home Page](./Frontend/public/Screenshot%202024-06-11%20113515.png)

# EXPENSE TRACKER

This project is a web application featuring user authentication, CRUD operations for transactions, and dynamic data visualization using charts. The backend is powered by Apollo Server and MongoDB, while the frontend is designed with a focus on user-friendly UI.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [License](#license)

## Technologies Used

**Frontend**: React, Chakra UI  
**Backend**: Node.js, Express.js, Apollo Server  
**Database**: MongoDB  
**Authentication**: Passport.js, JWT

## Installation

To get started with this project, follow the steps below:

### Prerequisites

- Node.js
- npm or yarn
- MongoDB

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/iamsufiyan560/expense-tracker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Frontend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables:

   Create a `.env` file in the root directory and add the following variables:

   ```env
   MONGO_URI ="YOUR MONGO URI"
   SESSION_SECRET = "YOUR SESSION SECRET"
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

## Features

### Authentication

- User signup
- User login
- User logout

### Transactions

- Create transactions
- Read transactions
- Update transactions
- Delete transactions

### Data Visualization

- Fetch and display real data for charts

### User Interface

- Complete UI design for signup, login, 404 page, and transaction pages

## Usage

To use the application, follow these steps:

1. Open your browser and navigate to `http://localhost:3000`.
2. Sign up for a new account or log in if you already have an account.
3. Use the transaction interface to manage your transactions.
4. View dynamic charts displaying your transaction data.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
