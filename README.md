# 🔝 Find Maximum Element in an Array using JavaScript

A simple JavaScript program that finds the **largest element in an array** using the built-in `Math.max()` function and the **spread operator (`...`)**.

This project demonstrates basic JavaScript functions, arrays, and modern ES6+ syntax.

---

## 📌 Overview

The program defines a reusable `MaxArray()` function that accepts an array of numbers and returns the maximum value.

For example:

```text
[10, 20, 30]
```

The maximum value is:

```text
30
```

---

## 🚀 Features

* Finds the largest element in an array
* Uses `Math.max()`
* Uses the JavaScript spread operator (`...`)
* Simple and reusable function
* Beginner-friendly implementation

---

## 🛠️ Technologies Used

* **JavaScript (ES6+)**
* `Math.max()`
* Spread Operator (`...`)

---

## 📂 Project Structure

```text
JavaScript-Max-Array/
│
├── maxArray.js
└── README.md
```

---

## 💻 Source Code

```javascript
function MaxArray(arr) {
    return Math.max(...arr);
}

console.log(MaxArray([10, 20, 30]));
```

---

## ▶️ How to Run

### Using Node.js

Make sure Node.js is installed on your system.

Run:

```bash
node maxArray.js
```

### Using a Browser

1. Open your browser.
2. Press `F12` to open Developer Tools.
3. Select the **Console** tab.
4. Paste the JavaScript code.
5. Press **Enter**.

---

## 📋 Sample Output

```text
30
```

---

## 🧠 How It Works

The function uses:

```javascript
Math.max(...arr);
```

The spread operator expands the array:

```text
[10, 20, 30]
```

into individual values:

```text
10, 20, 30
```

Then `Math.max()` finds the largest value:

```text
Math.max(10, 20, 30)
             ↓
            30
```

---

## 📖 Algorithm

1. Start the program.
2. Create an array of numbers.
3. Pass the array to the `MaxArray()` function.
4. Use the spread operator to expand the array elements.
5. Pass the values to `Math.max()`.
6. Return the maximum value.
7. Display the result using `console.log()`.

---

## ⏱️ Complexity Analysis

| Metric           | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(n)**   |
| Space Complexity | **O(n)**   |

`n` represents the number of elements in the array. The spread operation expands the array into individual arguments.

---

## 🎯 Concepts Covered

* JavaScript Functions
* Arrays
* `Math.max()`
* Spread Operator (`...`)
* Function Arguments
* `return` Statement
* Console Output

---

## 🔮 Future Improvements

* Find the minimum element
* Find both minimum and maximum elements
* Find the second-largest element
* Accept array input from the user
* Sort the array in ascending order
* Build an interactive web interface

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | Python | Java | JavaScript | SQL | Data Analytics

---

## 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and contribute for educational and learning purposes.

---

⭐ If you found this project helpful, don't forget to **Star** the repository!


<img width="874" height="640" alt="image" src="https://github.com/user-attachments/assets/d080b5f3-7d6f-4fa3-ba0c-7e3921b8a1ad" />

