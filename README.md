# Markdown-Guide-2025


# Markdown Syntax Guide
This guide provides a structured overview of **Markdown** syntax, accompanied by relevant examples. It covers `headings`, `lists`, `links`, `images`, `tables`, and other common elements used in Markdown.

## 1. Headings
Markdown allows you to create six levels of headings by using hash `(#)` symbols. The more `# symbols` you use, the smaller the heading.

# Heading 1 (Largest)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 (Smallest)

## 2. Paragraphs
To create paragraphs, simply write text separated by a blank line. No special characters are required.

This is a paragraph. It will be separated by a line break.
This is another paragraph.

## 3. Emphasis (`Bold`, `Italics`)
Use `asterisks (*)` or `underscores (_)` to add emphasis.

`Bold`: Use `**` or `__` around text.

`Italics`: Use `*` or `_` around text.

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_


## 4. Lists

- `Unordered Lists`: Use `-`,`*`, or `+` to create unordered lists.

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
- Item 3

- `Ordered Lists`
Use numbers followed by a period (1., 2., etc.) for ordered lists.

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
3. Third item

## 5. Links
You can create links using `square brackets []` for the link text and `parentheses ()` for the URL.

[The Final Markdown Guide 2025!]((https://github.com/amoreiraj/Markdown-Guide-2025/edit/main/README.md)m)

## 6. Images
Images are similar to links but with an `exclamation mark (!)` in front.
![Markdown Guide 2025](https://github.com/amoreiraj/Markdown-Guide-2025/edit/main/README.md))

## 7. Blockquotes
Use `> for blockquotes`. This is typically used to highlight quotes or important content.

 "This is a famous quote."
 - Author Name


## 8. Code
For inline code, use backticks `(```)`.
This is `inline code`.
For code blocks, use triple backticks `(```````)`.
This is a code block
with multiple lines

Alternatively, you can specify the language for syntax highlighting:

```python
def greet():
    print("Hello, World!")
yaml


---

## 9. Horizontal Rule

A horizontal rule is a line used to separate sections. You can create it with `three hyphens (`---`)`, `asterisks (`***`)`, or `underscores (`___`)`.

```markdown
---

## 10. Tables
You can create tables with pipes `(|)` and hyphens `(-)`. Use colons `(:)` to align columns.

| Name       | Age | City       |
|------------|-----|------------|
| Alice      | 25  | New York   |
| Bob        | 30  | San Francisco |
| Charlie    | 35  | Los Angeles |

- `Aligning Columns`:

| Name       | Age | City        |
|------------|-----|-------------|
| Alice      | 25  | New York    |
| Bob        | 30  | San Francisco |
| Charlie    | 35  | Los Angeles |

| Left Align  | Center Align  | Right Align |
|:------------|:--------------:|------------:|
| Left text   | Centered text | Right text  |
| More left   | More center    | More right  |


## 11. Task Lists
Task lists are useful for tracking progress. Use `square brackets [ ]` for tasks.


- [x] Task 1 (Completed)
- [ ] Task 2 (Not completed)
- [ ] Task 3 (Not started)


## 12. Footnotes
You can add footnotes by using a `^` symbol `followed by an identifier`, and then referencing that identifier.

Here is a sentence with a footnote[^1].
[^1]: This is the footnote text.

## 13. Strikethrough
Use `~~` around text to create a strikethrough effect.
~~This text is struck through~~

## 14. Emoji Support
You can use emojis in Markdown with the : syntax. Most Markdown editors support this.

:smile: :rocket: :heart:

## 15. HTML Elements
You can embed raw HTML into a Markdown document.

<div>
    <p>This is a custom HTML block</p>
</div>

