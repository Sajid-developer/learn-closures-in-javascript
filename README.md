# Learn Closure In JavaScript 
🌟 All about closure concept in JavaScript.

---

## 🧠 What is a Closure in JavaScript?

-> A closure is when a function remembers the variables from its outer (parent) function, even after that outer function has finished executing. 

### In Simple words
-> A function inside a function — that keeps access to its parent's variables.

---

## Example 👇🏻

```js 

function outer() {
  let name = "Sajid";

  function inner() {
    console.log("Hello " + name);
  }

  return inner;
}

const greet = outer(); // outer() returns inner function
greet(); // Output: Hello Sajid

```

---

## Show Your Support

If you find it helpful in your learning journey, please give it a star ⭐ to help others to discover it.

