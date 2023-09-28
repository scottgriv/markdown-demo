# Comprehensive Markdown Guide

This repository serves as a comprehensive guide to Markdown syntax. Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents.

---

## Table of Contents

- [Background on Markdown](#background-on-markdown)
- [Headers](#headers)
- [Emphasis](#emphasis)
- [Lists](#lists)
  - [Unordered Lists](#unordered-lists)
  - [Ordered Lists](#ordered-lists)
- [Links](#links)
- [Images](#images)
- [Code](#code)
  - [Inline code](#inline-code)
  - [Block code without syntax highlighting](#block-code-without-syntax-highlighting)
  - [Block code with syntax highlighting](#block-code-with-syntax-highlighting)
- [Tables](#tables)
- [Horizontal Rules](#horizontal-rules)
- [Blockquotes](#blockquotes)
- [Inline HTML](#inline-html)
- [Escaping Characters](#escaping-characters)
- [Task Lists](#task-lists)
- [Footnotes](#footnotes)
- [Definition Lists](#definition-lists)
- [Automatic URL Linking](#automatic-url-linking)
- [Emojis](#emojis)
- [Math Equations](#math-equations)
- [Abbreviations](#abbreviations)
- [Citations](#citations)
- [GitHub Flavored Markdown](#github-flavored-markdown)
  - [Alerts](#alerts)
- [References](#references)
- [Closing Remarks](#closing-remarks)
- [License](#license)

---

## Background on Markdown

Markdown is a lightweight markup language that was created by John Gruber and Aaron Swartz in 2004. The primary goal of Markdown is readability—the idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions.

Markdown has gained immense popularity over the years because of its simplicity and readability. It's widely used for writing README files, documentation, blog posts, forums, and even in chat applications.

### Why Use Markdown?

- **Readability**: Markdown's syntax is designed to be simple and intuitive.
- **Platform Independent**: You can use Markdown in a text editor, in a web editor, or as the formatting syntax for entire platforms.
- **Rich Output**: With simple syntax, you can produce rich text formatting.
- **Compatibility**: Many platforms automatically convert Markdown to HTML, making it easy to display rich text in a web browser.
- **Extensible**: While standard Markdown handles most common use cases, many platforms introduce their own extensions (called 'flavors') to add additional functionality like tables, code blocks, and more.

## Headers

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis

```markdown
*italic* or _italic_
**bold** or __bold__
**_bold and italic_**
~~strikethrough~~
```
*italic* or _italic_ <br>
**bold** or __bold__ <br>
**_bold and italic_** <br>
~~strikethrough~~ <br>

## Lists

### Unordered Lists

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b

*Or using dashes:*

```markdown
- Item 1
- Item 2
  - Item 2a
  - Item 2b
```
- Item 1
- Item 2
  - Item 2a
  - Item 2b

### Ordered Lists

```markdown
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

## Links

```markdown
[GitHub](http://github.com)
[GitHub with Title](http://github.com "GitHub")
```
[GitHub](http://github.com) <br>
[GitHub with Title](http://github.com "GitHub")

## Images

```markdown
![GitHub-Mark-Light](/docs/images/github-mark-white.png#gh-dark-mode-only)
![GitHub-Mark-Dark](/docs/images/github-mark.png#gh-light-mode-only)
```
![GitHub-Mark-Light](/docs/images/github-mark-white.png#gh-dark-mode-only) <br>
![GitHub-Mark-Dark](/docs/images/github-mark.png#gh-light-mode-only)

*Add #gh-light-mode-only or #gh-dark-mode-only to the end of the image link to make it only visible in light or dark mode, respectively.*

## Code: 

### Inline code:

```markdown
Here is `inline code`.
```
Here is `inline code`.

### Block code without syntax highlighting:

```markdown
```This is a block of code.```
```
```
This is a block of code.
```

### Block code with syntax highlighting:

```markdown
```python 
print("Hello, world!")
```

```python
print("Hello, world!")
```

## Tables

```markdown
| Header One     | Header Two     |
| -------------- | -------------- |
| Content Cell 1 | Content Cell 2 |
| Content Cell 3 | Content Cell 4 |
```
| Header One     | Header Two     |
| -------------- | -------------- |
| Content Cell 1 | Content Cell 2 |
| Content Cell 3 | Content Cell 4 |

## Horizontal Rules

Use three or more dashes, asterisks, or underscores:

```markdown
---
***
___
```
---
***
___

## Blockquotes

``` markdown
> This is a blockquote.
>
> > This is a nested blockquote.
```
> This is a blockquote.
>
> > This is a nested blockquote.

## Inline HTML

```html
<span style="color:red">This is red text.</span>
<div align="center">Centered Text</div>
```
<span style="color:red">This is red text.</span>
<div align="center">Centered Text</div>

## Escaping Characters
Backslash escapes Markdown characters:

```markdown
\*Not italic\*
\# Not a header
```
\*Not italic\* <br>
\# Not a header

## Task Lists

In GitHub Flavored Markdown, you can create task lists:

```markdown
- [x] Completed task
- [ ] Incomplete task
```
- [x] Completed task
- [ ] Incomplete task

## Footnotes

Some Markdown processors allow you to use footnotes, like so:

```markdown
Here's a sentence with a footnote. [^1]
[^1]: This is the footnote.
```
Here's a sentence with a footnote. [^1] <br>
[^1]: This is the footnote.

## Definition Lists

Not universally supported, but useful where available:

```markdown
Apple
:   Pomaceous fruit of plants of the genus Malus in the family Rosaceae.
Orange
:   The fruit of an evergreen tree of the genus Citrus.
```
Apple <br>
:   Pomaceous fruit of plants of the genus Malus in the family Rosaceae. <br>
Orange <br>
:   The fruit of an evergreen tree of the genus Citrus.

## Automatic URL Linking

Most Markdown processors will automatically turn URLs into links:

```markdown
http://www.example.com
```
http://www.example.com

## Emojis

On platforms that support it (like GitHub), you can use shorthand for emojis:

```markdown
:smile: :+1:
```
:smile: :+1:

## Math Equations

Some Markdown renderers like the one used by Jupyter Notebook support `LaTeX` for rendering math equations:

```markdown
```math
E = mc^2
```

```math
E = mc^2
```

## Abbreviations

Some extended Markdown processors allow abbreviations:

```markdown
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
```
*[HTML]: Hyper Text Markup Language <br>
*[W3C]:  World Wide Web Consortium

## Citations

Certain academic Markdown variants allow citations in `BibTeX` format:

```markdown
According to Smith [@smith04], blah blah...
[@smith04]: John Smith. 2004. The Book Title. Publisher Name.
```
According to Smith [@smith04], blah blah... <br>
[@smith04]: John Smith. 2004. The Book Title. Publisher Name.

## GitHub Flavored Markdown

### Alerts

GitHub Flavored Markdown supports alerts that can be used to highlight important information:

```markdown
  > [!NOTE]  
  > Highlights information that users should take into account, even when skimming.

  > [!IMPORTANT]  
  > Crucial information necessary for users to succeed.

  > [!WARNING]  
  > Critical content demanding immediate user attention due to potential risks.
```

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

## References

- [Markdown Guide](https://www.markdownguide.org/): A free and open-source reference guide that explains how to use Markdown.
- [Daring Fireball](https://daringfireball.net/projects/markdown/): The original Markdown project by John Gruber.
- [GitHub Flavored Markdown](https://github.github.com/gfm/): GitHub's variant of Markdown, which includes features like task lists and tables.
- [CommonMark](https://commonmark.org/): A strong specification of Markdown, designed to clarify many edge cases and inconsistencies in the original Markdown specification.
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet): A quick reference to Markdown syntax.
- [Pandoc](https://pandoc.org/): A universal document converter that supports Markdown and many other markup languages.
- [StackEdit](https://stackedit.io/): An in-browser Markdown editor.
- [Markdown Tutorial](https://chat.openai.com/?model=gpt-4#:~:text=browser%20Markdown%20editor.-,Markdown%20Tutorial,-%3A%20An%20interactive%20tutorial): An interactive tutorial to learn Markdown.
- [Jupyter Notebook](https://jupyter.org/): Although not strictly a Markdown resource, Jupyter Notebooks use Markdown for all non-code cells, making it a useful tool for scientific documentation where code and commentary are intermixed.
- [GitHub Markdown Alerts](https://blog.jakelee.co.uk/github-alert-experiments/)

## Closing Remarks

Remember, not all of these features are supported in every Markdown processor. Always check your specific processor's documentation for supported features.

You can use this as a README for your repository. Feel free to expand and improve the guide to better fit your requirements or to add more advanced features. Also, feel free to contribute and expand this guide for better community knowledge.

## License

- This project is released under the terms of the **MIT License**, which permits use, modification, and distribution of the code, subject to the conditions outlined in the license.
- The [MIT License](https://choosealicense.com/licenses/mit/) provides certain freedoms while preserving rights of attribution to the original creators.
- For more details, see the [LICENSE](LICENSE) file in this repository.

## Credits

**Author:** [Scott Grivner](https://github.com/scottgriv)<br>
**Email:** scott.grivner@nightowllabs.net<br>
**Website:** [nightowllabs.net](https://www.nightowllabs.net)<br>
**Reference:** [Main Branch](https://github.com/Night-Owl-Labs/LaTeX-Demo)
<div align="center">
    <a href="https://github.com/Night-Owl-Labs" target="_blank">
        <img src="./docs/images/NOL.png" style="width: 100px; height: 100px;" />
    </a>
</div>