<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Instructor Guide</span>
</h1>

## Lesson goal

This version is designed for **live instruction** rather than independent lab work.

Students should leave the lesson able to read basic Markdown syntax and create a useful `README.md` with headings, emphasis, lists, code, links, blockquotes, and images.

## Suggested pacing

| Section | Time | Teaching focus |
| ------- | ---- | -------------- |
| Setup | 10 min | Create the repository, starter `README.md`, and preview |
| Concepts | 5 min | Source text vs. rendered Markdown |
| Headings and Emphasis | 10 min | Demonstrate, then students edit |
| Lists and Code | 15 min | Spend extra time on fenced code blocks |
| Links and Blockquotes | 10 min | Link the MDN page and format the tip |
| Images and Extended Syntax | 10 min | Demonstrate image syntax; keep extended syntax brief |
| Practice | 15 min | Students create a second short tutorial |
| **Total** | **75 min** | |

## Teaching flow

Use the same pattern throughout the lesson:

1. Explain one Markdown feature.
2. Type one example while students watch.
3. Check the VS Code preview together.
4. Ask students to apply the same pattern to their own `README.md`.
5. Pause for a quick visual check before moving on.

Avoid explaining every Markdown feature before students type anything. The lesson works best when students see a small change immediately affect the rendered document.

## Key checkpoints

Before moving on, confirm that most students can see:

- the VS Code Markdown preview during setup
- a clear `#` and `##` heading hierarchy
- a bulleted list in the Basic syntax section
- syntax-highlighted JavaScript code blocks
- a clickable MDN link
- a rendered blockquote
- an image or a clear explanation of why an image path is broken

## Common issues

### The preview is not changing

Ask the student to save the file. Also confirm that the file ends in `.md`.

### The code block does not close

Check for three backticks before and after the code. If the student adds `javascript`, it should appear directly after the opening three backticks.

### A list does not render as a list

Check that there is a space after `-` or after the numbered list marker.

### A heading does not render

Check that there is a space between the `#` characters and the heading text.

### An image is broken

Check whether the student copied a web page URL instead of an image URL. For local images, check the file name and the relative path.

## Shorter 60-minute version

If time is limited:

- demonstrate the provided hosted image rather than asking students to find an image
- show tables, task lists, and strikethrough without requiring practice
- reduce the final tutorial to 10 minutes

Do not remove the lists-and-code section. Code formatting is one of the most useful Markdown skills for software engineering students.
