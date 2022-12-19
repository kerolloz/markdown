# GitHub Markdown Reference

## Headers

```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Lists

Unordered list

```markdown
- item
- item
- item
```

- item
- item
- item

---

Ordered list

```markdown
1. item
1. item
1. item
```

1. item
1. item
1. item

---

Nested lists

```markdown
- item
  - sub-item
    - sub-sub-item
```

- item
  - sub-item
    - sub-sub-item
    
## TODOs

```markdown
- [x] Learn Python
- [ ] Learn Java
```

- [x] Learn Python
- [ ] Learn Java

## Text Format

```markdown
*italic*
**bold**
~~strikethrough~~
```

*italic*  
**bold**  
~~strikethrough~~

## Images

```markdown
![Alternative text here](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1280px-Markdown-mark.svg.png)
```

![Alternative text here](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1280px-Markdown-mark.svg.png)

## Links

```markdown
checkout my [website](https://kerolloz.github.io/)
```

checkout my [website](https://kerolloz.github.io/)

## Image With link

```markdown
[![image alt text](https://i.imgur.com/sw215.jpeg)](https://imgur.com/gallery/sw215)
```

[![image alt text](https://i.imgur.com/sw215.jpeg)](https://imgur.com/gallery/sw215)


## Code

```markdown
this is a small `code` block
```

this is a small `code` block

----

This is a block of code with syntax highlighting: 

~~~~markdown
```python
print("Hello World")
```
~~~~

```python
print("Hello World")
```

## Block quote

```markdown
>look how this renders
```

>look how this renders

---

```markdown
>block one
>>nested block
```

>block one
>>nested block

## Table

Notice the colon `:` place

```markdown
left aligned | centered | right aligned
-------------|:--------:|--------------:
data         | data     | data
```

left aligned | centered | right aligned
-------------|:--------:|--------------:
data         | data     | data

## Horizontal Line

```markdown
up

---

down
```

up

---

down

## New line

You can make a new line by ending a line with *two spaces*, you don't have to use `<br>`.

## Note and Warning

The first line (`> **Note**` or `> **Warning**`) must be exactly as shown below.  
The first letter is case sensitive. The second line can contain your content.

```
> **Note**
> This is a note

> **Warning**
> This is a warning
```

Becomes:

> **Note**  
> This is a note

> **Warning**  
> This is a warning

---

## NOTE

In order to be able to see the effects of the tricks used in the following sections 
please view it from the [website](//kerolloz.github.io/markdown#definitions).

**Viewing it from GitHub's README won't show the effect!**

---

## Definitions

```markdown
Markdown
: Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML.
```

Markdown
: Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML.

## Abbreviations

```markdown
HTML is easy.

*[HTML]: Hyper Text Markup Language
```

HTML is easy.

*[HTML]: Hyper Text Markup Language

*<!-- a comment -->*

## Footnote

```markdown
the book [^1] has good exercises

[^1]: you can find the book on Google.

```

the book [^1] has good exercises

[^1]: you can find the book on Google.
