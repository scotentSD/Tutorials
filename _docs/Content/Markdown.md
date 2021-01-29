---
title: Markdown 101
category: Research
order: 1
---
## Summary
**Markdown** is a very simple way of taking notes and formatting them, using only the keyboard.

It allows "write once, use anywhere" functionality. 

## Contents
- [Summary](#summary)
- [Contents](#contents)
  - [Markdown Headings](#markdown-headings)
  - [Markdown Lists](#markdown-lists)
    - [Numbers will create an ordered list](#numbers-will-create-an-ordered-list)
  - [Links](#links)
  - [Adding a TOC](#adding-a-toc)

### Markdown Headings

Headings 1 to 6 are created by using the relevant numberof Hash (#) symbols in front of the text

```markdown
# Heading 1 (h1)
## Heading 2 (H2)
### Heading 3 (H3)
#### Heading 4 (H4)
```

will render as:
- # Heading 1 (h1)
- ## Heading 2 (H2)
- ### Heading 3 (H3)
- #### Heading 4 (H4)
These headings have been added to a **LIST**


### Markdown Lists

```ruby
- Item 1
- Item 2
-   Item 3
```

renders as 

- Item 1
- Item 2
- Item 3
  
Indenting is reflected in the list. 

Leave blank lines before and after most things

---

#### Numbers will create an ordered list
```ruby
1. Item 1
2. Item 2
  1. Item 3
```

renders as 

1. Item 1
2. Item 2
   1. Item 3

---

### Links

Links follow this format:

```ruby
[BBC NEWS](http://news.bbc.co.uk)
```

and will render as

- [BBC NEWS](http://news.bbc.co.uk)

---

### Adding a TOC

You can add links to other headings, (**Table of Contents**), in the same page using this format

```ruby
[Contents](#contents)
```

which will render as:

- [Contents](#contents)