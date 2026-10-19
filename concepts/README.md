<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Concepts</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to explain what Markdown is and why developers use it.

## What is Markdown?

Have you ever opened a GitHub repository and seen a nicely formatted `README.md` with headings, lists, code, links, and images?

That file is often written in **Markdown**.

Markdown is a lightweight markup language. It lets us add structure and formatting to plain text with simple characters such as `#`, `*`, `-`, and backticks.

For example, this plain Markdown:

```markdown
# Project Notes

This project uses **JavaScript**.
```

can render like this:

# Project Notes

This project uses **JavaScript**.

## Source text vs. rendered Markdown

When you write Markdown, you work with two views:

- **Source text** is the Markdown syntax you type.
- **Rendered Markdown** is the formatted result people see.

The browser or application reads the Markdown syntax and decides how to display it.

> 💡 Markdown keeps the source file readable even before it is rendered. This makes it useful for documentation that developers need to edit often.

## Where developers use Markdown

Developers commonly use Markdown for:

- GitHub `README.md` files
- project documentation
- technical tutorials
- notes and planning documents
- issue and pull request descriptions on platforms that support Markdown

Markdown is not a programming language. It does not create application logic. Its job is to organize and format written content.

## Our goal today

We will take the plain JavaScript tutorial from setup and improve it one step at a time.

After every change, look at the Markdown preview and ask:

**What syntax did I write, and what did it change in the rendered document?**
