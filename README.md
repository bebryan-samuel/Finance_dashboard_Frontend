# Personal Finance Dashboard

A responsive, modern **Personal Finance Dashboard** built using **HTML, CSS, and JavaScript**. It allows users to track income, expenses, and investments, with live visual analytics powered by **Chart.js**.

---

## 🚀 Features

### 💰 Dashboard Summary
- Total Balance with animated counter
- Monthly Income and Expense overview
- Investment portfolio snapshot

### 📋 Transaction Management
- Add new transactions with category and type (income, expense, investment)
- Real-time updates without page refresh
- Transaction table with delete functionality
- Category filtering and search bar
- Persistent data storage using **LocalStorage**

### 📊 Data Visualization
- **Pie Chart** – Expense breakdown by category
- **Line Chart** – Monthly spending trends
- **Bar Chart** – Income vs Expenses comparison

### 🧩 Technical Highlights
- Semantic **HTML5** structure
- **CSS Grid** and **Flexbox** for layout
- **Chart.js** for interactive charts
- **Mobile-first responsive design**
- **Smooth animations** and consistent theming

---

## 📁 Project Structure
```
Personal-Finance-Dashboard/
├── index.html       # Main dashboard structure
├── styles.css       # UI design and responsive styling
├── script.js        # Dynamic functionality and chart rendering
└── README.md        # Project documentation
```

---

## 🧠 How It Works
1. Transactions are stored in **LocalStorage** (no backend needed).
2. When a new transaction is added:
   - Balance and summaries update instantly.
   - Charts re-render in real time.
3. The data persists even after refreshing or closing the browser.

---

## 🛠️ Setup Instructions

### Option 1 — Local setup
1. Download or clone this repository.
2. Open the folder in your code editor.
3. Open `index.html` in your web browser.
4. Start adding transactions — your data will be saved automatically.

### Option 2 — Live Server (Recommended)
If you have VS Code:
- Install the **Live Server** extension.
- Right-click on `index.html` → `Open with Live Server`.

---

## 📈 Future Enhancements
- CSV/Excel export and import support
- Secure login & encryption for local data
- Dark mode toggle
- Multi-user or cloud sync option

---

## 🧾 License
MIT License © 2025 — You are free to use, modify, and distribute this project.

---

**Author:** Built with ❤️ using GPT-5 and Chart.js
