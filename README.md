# Bonus Calculator

## 🎯 Goal

Build a reusable bonus calculator that reads from a configuration object to determine bonus percentages for different roles and years of service.

## 🎥 Scenario:

HR wants the flexibility to **update bonus rules without changing the logic**, just the config. You'll build a function that:

- Accepts employee data
- Looks up their role in a bonus config
- Calculates and returns a personalized bonus message

## 📁 File Structure

You can keep everything in one file for now: `bonus-calculator.js`

## 👩🏻‍💼 Sample Employees

```js
const employees = [
  { name: 'Ella', role: 'Developer', years: 4 },
  { name: 'Mark', role: 'HR Manager', years: 3 },
  { name: 'Jules', role: 'Designer', years: 2 },
];
```

## ➡️ Stretch Goals

- Format the bonus amount as currency
