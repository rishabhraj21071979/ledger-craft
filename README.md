# FinancePulse

FinancePulse is a clean, user-friendly personal finance and expense-tracking website. It helps users manage their daily income, track expenses, and split bills easily within groups. 

---

## ✨ Key Features

*   **Dashboard Analytics:** View beautiful charts that summarize your monthly income and expenses.
*   **Smart Bill Splitting:** Create groups with friends or roommates to split bills and track who owes whom.
*   **Debt Minimization:** Features an automated system that reduces the number of transactions needed to settle up group balances.
*   **Secure Authentication:** Secure user signup and login systems, including Google Sign-In support.
*   **Asynchronous Reminders:** Automatic email alerts for upcoming bill due dates.

---

## 🛠️ Tech Stack Used

This application is built using the popular **MERN Stack**:
*   **Frontend:** React.js, Tailwind CSS (for modern UI styling), and Chart.js (for analytics).
*   **Backend:** Node.js and Express.js (handling API requests and business logic).
*   **Database:** MongoDB Atlas (storing users, groups, and transaction records securely in the cloud).

---

## 🚀 How to Run the Project Locally

Follow these quick steps to spin up the application on your own computer:

### 1. Pre-requisites
Make sure you have [Node.js](https://nodejs.org) installed on your machine.

### 2. Configure Environment Variables
Create a file named `.env` inside your `/backend` directory and add your secret keys:
```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_custom_secret_string
GOOGLE_CLIENT_ID=your_google_oauth_client_id
```

### 3. Install and Run the App
Open your terminal and run the backend and frontend servers:

```bash
# Set up and start the Backend Server
cd backend
npm install
npm start

# Open a new terminal tab, set up and start the Frontend
cd frontend
npm install
npm start
```

Once both servers are running, open your web browser and navigate to **`http://localhost:3000`** to view your live website!
