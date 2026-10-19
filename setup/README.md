<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Setup</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create a Markdown file and open a live Markdown preview in VS Code.

## Create the repository

We will use one `README.md` file throughout this lesson.

Navigate to your labs directory:

```bash
cd ~/code/ga/labs
```

On GitHub, create a new **public** repository named `intro-to-markdown`.

Do not add a `README.md` or `.gitignore` when you create the repository.

Copy the repository URL from GitHub, then clone it:

```bash
git clone https://github.com/<your-username>/intro-to-markdown.git
```

> 💡 Replace `<your-username>` with your GitHub username.

Move into the new directory and create a `README.md` file:

```bash
cd intro-to-markdown
touch README.md
code .
```

These commands work in **Git Bash on Windows** and in **zsh on macOS**.

## Add our starter content

Paste the following plain text into `README.md`.

Do not format it yet. We will add the Markdown syntax together during the lesson.

```text
Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

1. Basic syntax

const functionName = (params) => {
  // code to be executed
}

const: const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
Parameters: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
The body: The statements that make up the function itself. Surrounded by curly braces.

Example:

const greet = (name) => {
  console.log("Hello, " + name + "!")
}

Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData(), calculateArea(), or printReport().

2. Calling a function

To execute the function, you call or invoke it by using its name followed by parentheses.

Example:

greet('Fatima') // Outputs: Hello, Fatima!

3. Return values

Functions can process data input and output a value using the return keyword.

Example:

const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4)

console.log(total) // Expected value: 6

For more information on functions and how they are used in JS, check out the MDN docs.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
```

Save the file.

## Open the Markdown preview

VS Code can show the raw Markdown and its rendered result side by side.

Use this keyboard shortcut:

- **macOS:** `⌘ Command` + `K`, then `V`
- **Windows/Linux:** `Ctrl` + `K`, then `V`

You should now see your plain text on the left and a preview on the right.

> 🧠 Keep the preview open for the rest of the lesson. After every change, check what happened in the rendered document.

If the preview opens successfully, your setup is complete.
