<h1>
  <span class="headline">Intro to Markdown</span>
  <span class="subhead">Links and Blockquotes</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create links and use blockquotes to highlight important information.

## Links

A Markdown link has two parts:

```markdown
[Link text](https://example.com)
```

The text inside `[]` is what the reader sees.

The URL inside `()` is where the link goes.

For example:

```markdown
[MDN](https://developer.mozilla.org/)
```

## We Do: Link to the MDN documentation

At the bottom of your tutorial, you currently have a sentence and a separate URL.

Change them into one sentence with an inline link:

```markdown
For more information on functions and how they are used in JS, check out the [MDN docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions).
```

Save the file and click the link in your preview to test it.

## Reference-style links

Markdown also supports reference-style links.

```markdown
Read the [documentation][docs] before starting.

[docs]: https://example.com/
```

These can make a large document easier to read when the same link appears many times.

For today's tutorial, we will use the simpler inline link style.

## Blockquotes

A blockquote starts with `>` followed by a space.

```markdown
> This is an important note.
```

It renders as:

> This is an important note.

Blockquotes are useful for tips, warnings, short quotations, or important notes.

## We Do: Turn our tip into a blockquote

Find this line in the **Basic syntax** section:

```text
Tip: Functions often perform actions...
```

Add `> ` to the beginning:

```markdown
> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include `fetchData()`, `calculateArea()`, or `printReport()`.
```

Save the file and check the preview.

## 🎓 You Do

Add one more short blockquote anywhere in your tutorial.

It can be a note such as:

```markdown
> Remember: defining a function does not run it. We must call the function when we want it to execute.
```

Then save and check your preview.
