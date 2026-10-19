<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Images and Extended Syntax</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to add an image with alt text and recognize common extended Markdown syntax.

## Images

Image syntax looks similar to link syntax, but it starts with `!`.

```markdown
![Alt text](image-location)
```

The text inside `[]` is **alt text**. It should briefly describe the image.

> 💡 Good alt text helps people who use screen readers understand the purpose or content of an image.

## Hosted images

If an image is already hosted online, you can use its image URL:

```markdown
![Computer showing code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631)
```

## Relative image paths

If an image is stored inside the same repository, use a relative path.

For example, if the file structure looks like this:

```text
intro-to-markdown/
├── README.md
└── assets/
    └── workspace.jpg
```

we can write:

```markdown
![Developer workspace](./assets/workspace.jpg)
```

This lesson repository contains an example image at `assets/james-harrison-unsplash.jpg`.

It can be displayed from this lesson page with:

```markdown
![Computer showing code](../assets/james-harrison-unsplash.jpg)
```

![Computer showing code](../assets/james-harrison-unsplash.jpg)

## 🎓 You Do: Add an image

Choose one option:

1. Add the hosted image example above near the top of your tutorial.
2. Download an appropriate image, place it in an `assets` folder in your repository, and add it with a relative path.

Use clear alt text that describes the image.

## Extended Markdown syntax

Some Markdown platforms support extra formatting features. These are useful, but support can vary between platforms.

### Tables

```markdown
| Syntax | Purpose |
| ------ | ------- |
| `#` | Heading |
| `**` | Bold text |
```

This renders as:

| Syntax | Purpose |
| ------ | ------- |
| `#` | Heading |
| `**` | Bold text |

### Task lists

```markdown
- [x] Create repository
- [x] Add headings
- [ ] Push final work
```

This renders as:

- [x] Create repository
- [x] Add headings
- [ ] Push final work

### Strikethrough

```markdown
The old deadline was ~~Monday~~ Tuesday.
```

This renders as:

The old deadline was ~~Monday~~ Tuesday.

## 🎓 You Do: Try one extended feature

Add **one** of the following to the bottom of your tutorial:

- a small table
- a three-item task list
- one sentence using strikethrough

Save and check whether VS Code renders it as expected.

> 🧠 If a Markdown feature works in one platform but not another, check that platform's documentation. Extended Markdown syntax is not identical everywhere.
