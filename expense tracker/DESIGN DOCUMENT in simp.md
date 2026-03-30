Here’s your **DESIGN DOCUMENT** in **simple, easy words** 👇

---

# 📄 DESIGN DOCUMENT (Simple Version)

## 🧠 How the system works (Basic idea)

```
User → Website (Frontend) → Server (Backend) → Database
```

* User enters data (expense)
* Backend processes it
* Data is stored in database
* Website shows updated results

---

## 🎨 Pages in the Website

### 1. Login / Signup Page

* User enters email and password
* Can create a new account

---

### 2. Dashboard (Main Page)

Shows:

* Total balance
* Total expenses
* Recent transactions
* Charts (spending insights)

---

### 3. Add Expense Page

* Form to add expense
* Fields: Amount, Category, Date, Notes

---

### 4. Transactions Page

* List of all expenses
* Edit and delete options

---

### 5. Income Page (Optional)

* Add income
* View total income

---

## 🗂️ Database Design (Simple)

### Users Table

* id
* name
* email
* password

---

### Expenses Table

* id
* user_id
* amount
* category
* date
* notes

---

### Income Table

* id
* user_id
* amount
* date

---

## 🔄 How data flows

1. User logs in
2. User adds an expense
3. Backend saves it in database
4. Data is updated
5. Dashboard shows new data
6. Charts update automatically

---

## 📊 Charts Design

* Pie Chart → Shows where money is spent (Food, Travel, etc.)
* Bar Graph → Monthly expenses
* (Optional) Line Graph → Spending trend over time

---

## 🎯 Design Goals

* Simple and clean UI
* Easy to use
* Quick data entry
* Clear charts for understanding

---

## 📱 Responsiveness

* Works on mobile and laptop

---

## ✅ Final Output

User should easily:

* Add expenses
* View all transactions
* Understand spending using charts

---

If you want next level 👀
I can:
👉 Draw UI layout (like Figma design)
👉 Give frontend component structure (React)
👉 Or help you explain this in viva in 30 seconds 💯
