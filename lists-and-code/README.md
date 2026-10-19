<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Lists and Code</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create lists and format inline and multi-line code in Markdown.

## Lists

Lists help readers scan related information quickly.

### Unordered lists

Use `-`, `*`, or `+` followed by a space.

```markdown
- Planning
- Development
- Testing
```

This renders as:

- Planning
- Development
- Testing

### Ordered lists

Use a number followed by a period and a space.

```markdown
1. Create the repository
2. Write the code
3. Test the application
```

This renders as:

1. Create the repository
2. Write the code
3. Test the application

> 💡 Markdown can handle the numbering for you. Many Markdown renderers will still display `1.`, `2.`, `3.` even if every source line starts with `1.`.

## We Do: Turn the function parts into a list

In the **Basic syntax** section, turn the five function parts into an unordered list.

Your first item should look like this:

```markdown
- **const**: const should be used whenever a function expression is assigned to a variable.
```

Add `- ` to the beginning of the other four lines too.

Save and check the preview.

## Inline code

Use a single backtick when you mention a short piece of code inside a sentence.

```markdown
Use `console.log()` to print a value to the console.
```

This is useful for things such as:

- commands like `git status`
- filenames like `README.md`
- JavaScript keywords like `const`
- function names like `calculateArea()`

## Multi-line code blocks

For a larger code example, use three backticks before and after the code.

Add the language name after the opening backticks to get syntax highlighting.

````markdown
```javascript
const printItem = (item) => {
  console.log(item)
}
```
````

## We Do: Format the first code block

Find this code in `README.md`:

```text
const functionName = (params) => {
  // code to be executed
}
```

Wrap it in a JavaScript code fence:

````markdown
```javascript
const functionName = (params) => {
  // code to be executed
}
```
````

Check the preview. The code should now appear in its own formatted block.

## 🎓 You Do

1. Format the `greet` example as a JavaScript code block.
2. Format the `greet('Fatima')` example as a JavaScript code block.
3. Format the `addNums` example as a JavaScript code block.
4. Use inline code for at least three code terms in the explanation text, such as `const`, `params`, `fetchData()`, or `return`.
5. Save and check the preview.

> 🧠 Technical documentation should make code visually different from normal writing. Readers should be able to find code examples quickly.
