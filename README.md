# 💰 Smart Budget Planner

> A simple and interactive web-based financial planning tool that helps you organize your income, savings, expenses, and monthly budget in one place.

---

## 📌 About the Website

**Smart Budget Planner** is a personal finance planning website designed to make monthly budgeting easier and more organized.

Instead of manually calculating how much money is available after savings and expenses, the website automatically processes the information entered by the user and provides a clear overview of their financial plan.

The website allows users to:

- 💵 Enter their monthly income
- 💱 Choose their preferred currency
- 🎯 Set a savings goal
- 💰 Track how much they have already saved
- 📅 Set an optional savings timeline
- 🧾 Add and manage monthly expenses
- 📊 Monitor their budget in real time
- ⚠️ Identify when expenses go over the available budget
- 💡 View a recommended budget when spending exceeds the plan
- 📈 Review their complete financial overview

The goal is to provide a **simple, clear, and practical budgeting experience** without making financial planning complicated.

---

## ✨ Key Features

### 💵 Income & Savings

- Enter monthly income
- Select from multiple currencies
- Set a savings target
- Select a savings purpose
- Enter existing savings
- Set a savings timeline
- Automatically calculate the remaining amount
- Calculate the required monthly savings
- Track savings progress
- Add additional savings whenever needed

### 🧾 Expense Management

Users can add their expected monthly expenses and organize them into categories such as:

- 🍔 Food
- ✈️ Travel
- 🛍️ Shopping
- 🏨 Hotel
- 🏠 Rent
- 🎓 Education
- 🚌 Transport
- 💳 Bills
- ❤️ Health
- 📦 Other

The website also allows users to:

- ➕ Add expenses
- ✏️ Edit expenses
- 🗑️ Delete expenses
- 🏷️ Create custom expense categories
- 🔄 Automatically update expense totals

---

## 📊 Budget Review

The website analyzes the user's financial plan based on:

**Monthly Income − Planned Savings − Expenses**

It provides:

- 💰 Available budget
- 💸 Total expenses
- 💵 Remaining money
- 📅 Daily spending limit
- 🟢 Within Plan status
- 🟡 Needs Attention status
- 🔴 Over Budget status

When planned expenses exceed the available budget, the website can provide a **recommended budget allocation** to help the user review their spending plan.

The user can then choose whether to apply the recommendation or keep their original budget.

---

## 📈 Financial Overview

The Financial Overview section provides a clear summary of the user's budget.

It includes:

- Monthly Income
- Planned Savings
- Total Expenses
- Money Remaining
- Daily Spending Limit
- Expense Breakdown
- Planned vs. Suggested Budget

This gives the user a quick view of their overall financial position.

---

## 💾 Data Management

The website uses browser-based storage to make the experience more convenient.

Users can:

- 💾 Save their budget
- 🔄 Load saved information
- 🧹 Clear saved information
- 🆕 Start a new budget

Budget information is stored locally in the user's browser using **LocalStorage**.

---

## 💱 Supported Currencies

Smart Budget Planner supports multiple currencies:

| Currency | Symbol |
|---|---|
| INR | ₹ |
| USD | $ |
| EUR | € |
| GBP | £ |
| JPY | ¥ |
| CNY | ¥ |
| CAD | C$ |
| AUD | A$ |
| SGD | S$ |
| AED | د.إ |
| CHF | CHF |
| KRW | ₩ |
| NZD | NZ$ |
| ZAR | R |
| BRL | R$ |

> Currency selection changes the displayed currency format. The website does not perform currency conversion.

---

## 🛠️ Technologies Used

- **HTML5** — Website structure
- **CSS3** — Styling, layout, and responsive design
- **JavaScript** — Calculations, interactions, and application logic
- **LocalStorage** — Client-side data persistence
- **Git** — Version control
- **GitHub** — Source code management
- **GitHub Pages** — Deployment

---

## 📂 Project Structure

```text
SMART-BUDGET-PLANNER/
│
├── index.html
└── README.md
