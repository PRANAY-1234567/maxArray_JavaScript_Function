📘 README — maxArray JavaScript Function

📌 Description

This code defines a simple JavaScript function maxArray that finds and returns the largest number from an array of numbers.

It uses JavaScript’s built-in Math.max() method along with the spread operator (...) to compare all values in the array.

⚙️ How the Code Works

function maxArray(arr) {
  return Math.max(...arr);
}

console.log(maxArray([10, 50, 20]));
Step-by-Step:

The function maxArray takes an array arr as input.

The spread operator (...arr) expands the array into individual values.

Example: [10, 50, 20] → 10, 50, 20

Math.max() checks all values and returns the highest one.

The result is printed using console.log().

▶️ Example Output

Input:

[10, 50, 20]

Output:

50
✅ Requirements

JavaScript ES6 or later (because of spread operator)

💡 Use Cases

Finding highest marks in a list

Getting maximum sales value

Any scenario where you need the largest number from a dataset

🚀 Quick Tip

If the array might be empty, you should handle it like this:

function maxArray(arr) {
  return arr.length ? Math.max(...arr) : null;
}
👨‍💻 Author

Pranay Jadhao

<img width="874" height="640" alt="image" src="https://github.com/user-attachments/assets/d080b5f3-7d6f-4fa3-ba0c-7e3921b8a1ad" />

