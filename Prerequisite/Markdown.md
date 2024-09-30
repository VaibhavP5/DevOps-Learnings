
# Markdown Guide

**Welcome to the Markdown Guide!**
Markdown is a lightweight markup language that makes it easy to create formatted text using plain text. It’s widely used in documentation, wikis, blogs, and readme files. This guide will help you get started with Markdown for creating clean and readable documents.

## :pen: Basic Syntax
## :memo: Headings
- **Syntax:**
```md
    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6
```
- **Result:**
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

## :dizzy: Emphasis
- **Syntax:**
```md
    This is **Bold Text**
    This is *Italic Text*
    This is ***This is Bold + Italic Text***
    This is ==Highlighted Word==
    This is ~~Strikethrough~~

```
- **Result:**
This is **Bold Text**.

This is *Italic Text*.

This is ***This is Bold + Italic Text***.

This is <mark>Highlighted Word</mark>.

This is ~~Strikethrough~~.

- **Superscript:** **`x<sup>2</sup>+y<sup>2</sup>=?`**
        - Result: **x<sup>2</sup>+y<sup>2</sup>=?**
- **Subscript:** `H<sub>2</sub>O`
        - Result: **H<sub>2</sub>O**

---

## :eyes: Emojis
- **Syntax with Output:** 

`:smile:` : :smile:

`:angry:` : :angry:

`:rocket:` : :rocket:

`:cloud:` : :cloud:

- Checkout All Emoji Name list here: [Markdown Emoji List](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

---

## :computer: Code Blocks
- **Syntax:**
```Use `git status` to check your repository status.```
- **Result:**
Use `git status` to check your repository status.

### MultiLine Code:
- **Syntax:** Use of (```)Three Backticks at start and end of code block.
```py
(```)
name = "Vaibhav"
print(name)
(```)
```
**Note: Avoid the Parentheses.**

- **Result:**
```py
name = "Vaibhav"
print(name)
```

---

## :page_with_curl: Quotes
- **Syntax:**
``` > This is BlockQuotes```
``` >> This is Nested BlockQuotes```
``` >>> Another Nested Line```
- **Result:**

> This is BlockQuotes  

>> This is Nested BlockQuotes  

>>> Another Nested Line  


---

## :link: Links & Images
### 1. Links
- **Syntax:**
`[Visit Google](https://www.google.com)`
- **Result:**
[Visit Google](https://www.google.com)

### 2. Images
- **Syntax:**
`![Markdown Logo](https://markdown-here.com/img/icon256.png)`
- **Result:**
![Markdown Logo](https://markdown-here.com/img/icon256.png)

---

## Lists
### Unordered List

- **Syntax:**
```
- Item 1
- Item 2
    - Subitem 2.1
    - Subitem 2.2
        - Names
        - Marks
            1. In Numeber
            2. In Words
```
- **Result:**

- Item 1
- Item 2
    - Subitem 2.1
    - Subitem 2.2
        - Names
        - Marks
            1. In Numeber
            2. In Words

### Ordered List

- **Syntax:**
```
1. First Item
2. Second Item
    1. Subitem 2.1
```
- **Result:**

1. First Item
2. Second Item
    1. Subitem 2.1

---

## :bar_chart: Tables
- **Syntax:**
```
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |
```
- **Result:**

| **Column 1** | **Column 2** | **Column 3** |
| :---: | :---: | :---: |
| Data 1 | Data 2 | Data 3 |
| Data 4 | Data 5 | Data 6 |

---

## :books: Additional Features
### 1. Horizontal Line
- Use `---` or `***` for a Horizontal line.
- **Result:**
---

### 2. Task Lists
- Use `- [ ]` for Unchecked task and `- [x]` for Checked task.
```
- [ ] Task 1
- [x] Task 2
```
- **Result:**
- [ ] Task 1
- [x] Task 2

---

- **Hands-On Markdown:** [Markdown Live Preview](https://markdownlivepreview.com/)

## :tada: Wrapping Up
**We've covered the Essential Concepts of Markdown! With these concepts you can create well-structured, readable documentation for your projects.**

**Happy Documenting! :blush:**
   