<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Headings and Emphasis</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create headings and use bold and italic text to organize a Markdown document.

## Headings

Headings give a document structure.

In Markdown, a heading starts with one or more `#` symbols followed by a space.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

The number of `#` symbols controls the heading level.

> 🧠 Use heading levels in order. A document normally has one main `#` heading, with `##` headings for major sections underneath it.

## We Do: Structure our tutorial

In `README.md`, change the first line:

```text
Writing a Function in JavaScript
```

to:

```markdown
# Writing a Function in JavaScript
```

Next, change the three section titles to level-two headings:

```markdown
## 1. Basic syntax
## 2. Calling a function
## 3. Return values
```

Save the file and check the preview.

The tutorial should now have a clear visual hierarchy.

## Emphasis

Markdown gives us simple ways to emphasize words.

### Bold

Wrap text with two asterisks:

```markdown
This text is **bold**.
```

### Italic

Wrap text with one asterisk:

```markdown
This text is *italic*.
```

### Bold and italic

Wrap text with three asterisks:

```markdown
This text is ***bold and italic***.
```

## We Do: Emphasize important terms

In the **Basic syntax** section, find these five labels:

```text
const:
The function name:
Parameters:
The arrow syntax:
The body:
```

Make the words before each colon bold.

For example:

```markdown
**Parameters**: Optional comma separated parameters...
```

## 🎓 You Do

Update the remaining text in your tutorial:

1. In **Calling a function**, make the words *call* and *invoke* italic.
2. In **Return values**, make the word *return* italic when it is introduced.
3. Find each `Example:` label and choose either **bold**, *italic*, or ***bold and italic*** formatting for it.
4. Save your file and check the preview before moving on.
