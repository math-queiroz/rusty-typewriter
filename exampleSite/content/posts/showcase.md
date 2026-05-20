+++
title = 'Showcase'
date = '2025-03-24T23:00:00-03:00'
tags = ['example']
series = ['styling']
weight = 3
+++

This page focuses on what you can do in terms of markdown syntax. Here you can see which and how each of the components are rendered to HTML in terms of structure and styling.

# The use of Headings

Headings are larger text intended for section titles, and they vary in size from 1 to 5 (bigger to smaller) as follows:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

###### Heading 5

## Paragraphs

Paragraphs are containers for standard page content. Its font is defined and configurable via CSS as mentioned in [customization](/features/customization) post.

## Lists

### Ordered

1. First item
2. Second item  
  2.1. First nested item
3. Third item

### Unordered

- Unordered Item
- Another Item
- Yet another

## Tables

| Id | Keys  | Data    |
| :- | :-    | :-:     |
| 1  | Key 1 | Value 1 |
| 2  | Key 2 | Value 2 |
| 3  | Key 3 | Value 3 |

## Code 

### Inline Code

Inline code looks like this: `inline-code-example`. Defined by enclosing text in backticks (`), it's enclosed in a different color and with monospaced font.

### Code Block

Code blocks support syntax highlighting for plenty of languages.

```yaml
yaml:
  syntax:
    highlighted:
      so: cool!
```

## Media

Media like images may be inserted using the syntax `![alt](/images/file.png)`

![landscape](/images/landscape.png)

## Blockquotes

> Blockquotes, with support for markdown syntax like **bold text**, ~strike through~, [links](#) and *others*.  
> — Here, Some name
