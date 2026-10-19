<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Practice</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to use common Markdown syntax to create a clear technical document without step-by-step instructions.

## Check your first tutorial

Before starting a new document, compare your work with the checklist below.

Your JavaScript tutorial should now include:

- one `#` main heading
- three `##` section headings
- bold text
- italic text
- a list
- inline code
- JavaScript code blocks
- an MDN link
- a blockquote
- an image
- at least one extended Markdown feature

<details>
<summary>Open a finished example</summary>

# Writing a Function in JavaScript

![Computer showing code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax

```javascript
const functionName = (params) => {
  // code to be executed
}
```

- **const**: `const` should be used whenever a function expression is assigned to a variable.
- **The function name**: The name you choose for the function.
- **Parameters**: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the `()` is still required.
- **The arrow syntax**: Indicates that this will be a function.
- **The body**: The statements that make up the function itself. Surrounded by curly braces.

*Example:*

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!")
}
```

> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include `fetchData()`, `calculateArea()`, or `printReport()`.

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

*Example:*

```javascript
greet('Fatima') // Outputs: Hello, Fatima!
```

> Remember: defining a function does not run it. We must call the function when we want it to execute.

## 3. Return values

Functions can process data input and output a value using the *return* keyword.

*Example:*

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4)

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).

</details>

## 🎓 You Do: Create a second tutorial

Create a new Markdown file:

```bash
touch tutorial.md
```

Choose a short technical topic you already understand.

For example:

- How to create an HTML boilerplate
- How to use a CSS class selector
- How to create a file from the Terminal
- How to check the status of a Git repository
- How to create and switch to a Git branch

Your new tutorial should include:

- a clear `#` title
- at least two `##` section headings
- bold or italic text
- a list
- inline code
- at least one fenced code block
- at least one link
- at least one blockquote

You may also add an image, table, task list, or strikethrough.

Keep the tutorial short. The goal is to practice Markdown, not to write a long article.

## Commit and push your work

When you are finished:

```bash
git status
git add .
git commit -m "complete markdown lesson"
git push
```

Open your repository on GitHub.

Check that `README.md` is rendered correctly on the repository page. Then open `tutorial.md` and check that it renders correctly too.

> 🧠 A good developer habit is to read your documentation from the user's point of view after you push it. Check headings, links, code blocks, and image alt text before considering the work complete.
