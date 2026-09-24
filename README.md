# goit-js-hw-03

Homework assignment #3 from the [GoIT](https://goit.global/) JavaScript course. A set of three small exercises practicing string and array manipulation in vanilla JavaScript.

## 📋 About

Each task is implemented as a standalone function that is called with sample inputs, logging the result to the console:

- **Task 1** — `slugify(title)`: converts a title into a URL-friendly slug by lowercasing it and replacing spaces with hyphens.
- **Task 2** — `makeArray(firstArray, secondArray, maxLength)`: concatenates two arrays and trims the result to a maximum length if needed.
- **Task 3** — `filterArray(numbers, value)`: returns a new array containing only the numbers greater than a given value.

## 🛠️ Tech Stack

- Vanilla JavaScript (ES modules)
- HTML5

## 📁 Project Structure

```
goit-js-hw-03-main/
├── js/
│   ├── task-1.js    # Title-to-slug converter
│   ├── task-2.js    # Array concatenation with length limit
│   └── task-3.js    # Array filtering by threshold value
├── .prettierrc.json   # Prettier configuration
└── index.html          # Loads all three task scripts as ES modules
```

## 🚀 Getting Started

Open `index.html` in a browser and check the browser console (DevTools) to see the logged results of each task.
