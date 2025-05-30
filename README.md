# 📝 Markdown Syntax Guide 2025



A clear and structured overview of **Markdown** syntax with helpful examples. This guide covers `headings`, `lists`, `links`, `images`, `tables`, `code`, and more.

---

## 📌 1. Headings

Use `#` symbols (1–6) to create headings. The more `#`, the smaller the heading.
```markdown
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6
```

➡️ Output:
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6

----

## ✏️ 2. Paragraphs

Just write text separated by a blank line.

```markdown
This is a paragraph.

This is another paragraph.
```

---

## 💬 3. Emphasis (`Bold`, `Italics`)
Use asterisks `*`, `**`, underscores `_`, or `__` to add emphasis.

```markdown
`Bold`: Use `**` or `__` around text.

`Italics`: Use `*` or `_` around text.
```

➡️ Output: 
**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

---

## ✅ 4. Lists

### - `Unordered Lists`: Use `-`,`*`, or `+` to create unordered lists.

```markdown
- Item 1  
- Item 2  
  - Subitem  
- Item 3
```

### - `Ordered Lists`
Use numbers followed by a period (1., 2., etc.) for ordered lists.

```markdown
1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
3. Third item
```

---

## 🔗 5. Links
You can create links using square brackets `[]` for the link text and parentheses `()` for the URL.

```markdown
➡️ Example:  [The Final Markdown Guide 2025!]((https://github.com/amoreiraj/Markdown-Guide-2025/edit/main/README.md)m)
```
---

## 🖼️ 6. Images
Images are similar to links but with an exclamation mark `(!)` in front.

```markdown
➡️ Example: ![Markdown Guide 2025](https://github.com/amoreiraj/Markdown-Guide-2025/edit/main/README.md))
```
---

## 💬 7. Blockquotes
Use `> for blockquotes`. This is typically used to highlight quotes or important content.

```markdown
> This is a blockquote.  
> – Author Name
```

➡️ Output:

> "This is a blockquote."  
> – Author Name

---

## 💻 8. Code
### Inline:

```markdown
`inline code`
```

➡️ Example: `inline code`

### Code Block:
```markdown
<pre>
```python
def greet():
    print("Hello, World!")
```
</pre>
```
➡️ Output:

```python
def greet():
    print("Hello, World!")
```

---

## 📏9. Horizontal Rule

A horizontal rule is a line used to separate sections. You can create it with `three hyphens (`---`)`, `asterisks (`***`)`, or `underscores (`___`)`.

```markdown
---
```

## 📊10. Tables
You can create tables with pipes `(|)` and hyphens `(-)`. Use colons `(:)` to align columns.

```markdown
| Name       | Age | City       |
|------------|-----|------------|
| Alice      | 25  | New York   |
| Bob        | 30  | San Francisco |
| Charlie    | 35  | Los Angeles |
```

### - `Aligning Columns`:

```markdown
| Name       | Age | City        |
|------------|-----|-------------|
| Alice      | 25  | New York    |
| Bob        | 30  | San Francisco |
| Charlie    | 35  | Los Angeles |
```
```markdown
| Left Align  | Center Align  | Right Align |
|:------------|:--------------:|------------:|
| Left text   | Centered text | Right text  |
| More left   | More center    | More right  |
```

➡️ Output:

| Left     | Center   | Right    |
|:-------- |:--------:| -------:|
| Alice        |Bob           | Charlie       |

---

## 📋 11. Task Lists
Task lists are useful for tracking progress. Use `square brackets [ ]` for tasks.

```markdown
- [x] Task 1 (Completed)
- [ ] Task 2 (Not completed)
- [ ] Task 3 (Not started)
```
➡️ Output:

- [x] Task 1  
- [ ] Task 2  
- [ ] Task 3
      
---
      
## 🔢 12. Footnotes
You can add footnotes by using a `^` symbol `followed by an identifier`, and then referencing that identifier.

```markdown
Here is a sentence with a footnote[^1].
[^1]: This is the footnote text.
```
---

## ❌ 13. Strikethrough
```markdown
Use `~~` around text to create a strikethrough effect.
~~This text is struck through~~
```
---

## 😀 14. Emoji Support
You can use emojis in Markdown with the : syntax. Most Markdown editors support this.

```markdown
:smile: :rocket: :heart:
```
➡️ Output:  
:smile: :rocket: :heart:

---

## 🔧 15. HTML Elements
You can embed raw HTML into a Markdown document.
```markdown
```html
<div>
  <p>This is a custom HTML block</p>
</div>
```
```
➡️ Output:

<div>
  <p>This is a custom HTML block</p>
</div>

