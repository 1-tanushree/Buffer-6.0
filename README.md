# Finance Tracker

### Built by Team Code Red

A smart web-based tool that helps users track daily income and expenses, calculate total savings, and get personalized investment suggestions using efficient Data Structures.

---

## Features

- Add daily income and expense transactions
- Calculate total savings instantly
- Get smart investment suggestions:
  - Digital Gold (if savings > ₹5000)
  - Mutual Funds (if savings ≤ ₹5000)
- Includes helpful YouTube links to learn about investments

---

## Data Structure Used

We use a Fenwick Tree (Binary Indexed Tree) for:
- Fast updates of day-wise transactions
- Efficient prefix sum queries to compute total savings across a month (31 days)

Positive amount → Income  
Negative amount → Expense  
Total Savings = Sum of all values from Day 1 to Day 31

---

## Tech Stack

- Frontend: React.js  
- Backend: Node.js, Express  
- Data Structure: Fenwick Tree (custom implementation in JS)  
- Deployment: Runs locally (localhost:3000 for frontend, localhost:5000 for backend)

---

## How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/finance-tracker.git
cd finance-tracker

