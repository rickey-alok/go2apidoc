icon: material/language-markdown

# Markdown - Cheat sheet

## Headings

Input

```
# H1

## H2

### H3

#### H4

##### H5

###### H6

Header 1
==========

Header 2
-----------
```

Output

```code

# H1

## H2

### H3

#### H4

##### H5

###### H6

# Header 1

## Header 2
```

---

## Formatting

`Normal` = Normal

`**Bold**` = **Bold**
`__Bold__` = **Bold**

`*Italic*` = _Italic_
`_Italic_` = _Italic_

`***Bold & Italics***` = **_Bold & Italics_**
`___Bold & Italics___` = **_Bold & Italics_**

`Subscript example: H~2~O` = H~2~O

`Superscript example: X^2^` = X^2^

`==Highlight==` = ==Highlight==

`~~Strikethrough~~` = ~~Strikethrough~~

## Emojis

`:joy:` = 😂

`:smile:` = 😄

`:cry:` = 😢

`:tent:` = ⛺️

`:heart:` = ❤️

`:icecream:` = 🍦

`:school:` = 🏫

`:car:` = 🚗

## List

### Ordered list

Input

```

1. Item 1
2. Item 2
   1. Item 2.1
      1. Item 2.1.a
      2. Item 2.1.b

```

Output

1. Item 1
2. Item 2
   1. Item 2.1
      1. Item 2.1.a
      2. Item 2.1.b

### Unordered list

Input

```

- Item 1
- Item 2
  - second level 1
    - third level
  - second level 2
    - third level

```

Output

- Item 1
- Item 2
  - second level 1
    - third level
  - second level 2
    - third level

### Task List:

Input

```

- [ ] Checkbox off
- [x] Checkbox on

```

Output

- [ ] Checkbox off
- [x] Checkbox on

---

Miscellaneous

Input

```

term
: definition

```

Output

term
: definition

## Code

### Inline Code

Input

```

`code`

```

Output

`code`

### Block Code

## JSON

### Code block with JSON keyword

Input

````

```JSON
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

````

Output

```JSON
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Code block without JSON keyword

Input

````

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

````

Output

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Links

### External reference

Input

```
[Google](https://www.google.com)
```

Output

[Google](https://www.google.com)

Input

```
[Google](https://www.google.com "Google Home Page")
```

Output

[Google](https://www.google.com "Google Home Page")

Input

```
<https://google.com>
```

Output

<https://google.com>

### Internal Reference

Input

```
[Linked to readme page](## "link")
```

Output

[Linked to readme page](## "link")

## Images

### External reference

Input

```
![water](https://media.istockphoto.com/photos/underwater-bubbles-picture-id925440650?k=20&m=925440650&s=612x612&w=0&h=OYU-poM2bI0xYJvb8qRAQ5UCc3qvnYt91KNv4nCOjgY=)
```

Output

![water](https://media.istockphoto.com/photos/underwater-bubbles-picture-id925440650?k=20&m=925440650&s=612x612&w=0&h=OYU-poM2bI0xYJvb8qRAQ5UCc3qvnYt91KNv4nCOjgY=)

### Internal Reference

Input

```
![git-logo](../img/git-logo.png)
```

Output

![git-logo](../img/git-logo.png)

## Table

### Alignment

You can align text in the columns to the left, right, or center by adding a colon `:` to the left, right, or on both side of the hyphens within the header row.

| Syntax            |     Description     |          Test Text |
| :---------------- | :-----------------: | -----------------: |
| Text Left Aligned | Text Center Aligned | Text Right Aligned |

## Blockquote

Input

```
> This is
> a blockquote
>
> > Nested
> > Blockquote
```

Output

> This is
> a blockquote
>
> > Nested
> > Blockquote

## Horizontal Rule

Input

```
Three or more

--- (Hyphens) or *** (Asterisks) or ___ (Underscores)
```

Output

---

## Footnote

Input

```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

Output

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

## Markdown in HTML

Does _not_ work **very** well. Use HTML tags.

```

```

```

```

```

```
