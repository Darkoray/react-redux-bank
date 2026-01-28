# 🏦 The React-Redux Bank ⚛️ [![wakatime](https://wakatime.com/badge/user/72594c02-0009-4d68-ba8b-6bc52b500d86/project/20a8da7e-ab96-448f-9231-f1b69c52bbf3.svg)](https://wakatime.com/badge/user/72594c02-0009-4d68-ba8b-6bc52b500d86/project/20a8da7e-ab96-448f-9231-f1b69c52bbf3)

A banking application built with React and Redux. Users can create customers, accounts, and perform various operations on accounts. The app displays the current balance of the account.

---

## How to Use

- Go to the website: [The Redux Bank](https://darkoray.github.io/redux-intro/)
- Create a customer with their details
- Create a new account for the customer
- Perform account operations like deposit, withdraw, and check the balance

---

## ✨ Features

- **Create a Customer**: Users can create new customers with their details.
- **Create an Account**: Users can create new accounts for the customer.
- **Account Operations**: Users can deposit money into their account, withdraw money from their account, and check the balance of their account.
- **Balance Display**: The app displays the current balance of the account.

---

## 🖼️ Layouts

These components define the structural foundation of the application.

- `App.jsx`: The main component that renders the different features of the bank.
- `CreateCustomer.jsx`: A form that allows users to create new customers.
- `Customer.jsx`: Displays the details of a customer and the accounts associated with the customer.
- `AccountOperations.jsx`: A form that allows users to perform operations on an account.
- `BalanceDisplay.jsx`: Displays the current balance of the account.

---

## ⚙️ Utilities

These are smaller, reusable components for general use.

- `Balance`: A component that displays the current balance of the account.
- `Input`: A reusable input component.
- `Button`: A reusable button component.

---

## 🛠️ Technologies Used

- **React 18** : Modern JavaScript library for building user interfaces.
- **Redux** : Predictable state container for managing global state.
- **Redux Toolkit** : A set of APIs to simplify using Redux with React.

---

---

## 📂 Project Structure

```
src/
├─ features/
│  ├─ accounts/
│  │  ├─ AccountOperations.jsx
│  │  ├─ accountSlice.jsx
│  │  └─ BalanceDisplay.jsx
│  └─ customers/
│     ├─ CreateCustomer.jsx
│     ├─ Customer.jsx
│     └─ customerSlice.jsx
├─ App.jsx
├─ index.css
├─ index.js
└─ store.jsx
```

---

## 📄 License & Credits

This project is provided for **learning purposes only**.

© by You. You can use it for your portfolio or learning. Do not use it to teach or redistribute as your own work.
