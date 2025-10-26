# Travel-List

A simple and interactive React app to help you organize everything you need for your next trip!
Add items, mark them as packed, sort your list, and clear everything once you’re ready to go.

---

## Description

**Travel-List** is a React project I built while learning about **state and state management**.
It’s designed to make packing easier and to help me practice how data flows between React components.

This project taught me how to use **React’s `useState` hook**, manage dynamic lists, handle user input, and build reusable components that work together.

---

## Features

- Add items with quantity and description
- Mark items as packed/unpacked
- Sort items by input order, name, or packed status
- Delete individual items
- Clear the entire list with confirmation
- View real-time packing progress and stats

---

## What I Learned

While building this app, I learned:

- How to use **React’s `useState`** for managing local component data
- How to **update, delete, and toggle state values**
- How to **pass functions and data through props**
- How to **split components** into separate files for better structure
- How to design **clean component-based UIs**

---

## Project Structure

```
src/
├── components/
│   ├── App.js
│   ├── Form.js
│   ├── Item.js
│   ├── Logo.js
│   ├── PackingList.js
│   └── Stats.js
├── index.css
└── index.js
```

---

## Getting Started

1. Clone the repository

   ```bash
   git clone https://github.com/raghadislam/travel-list.git
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Run the app locally

   ```bash
   npm start
   ```

4. Open **[http://localhost:3000](http://localhost:3000)** to use Travel-List in your browser
