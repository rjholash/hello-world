# Markdown Cheat Sheet... as copied from the markdown guide below. Toggle the edit icon to see the original text

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Heading

# H1
## H2
### H3

### Bold

**bold text**

### Italic

*italicized text*

### Blockquote

> blockquote

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block
! you should notice in the block below doing this on github allows you to copy the code popup on the top right of the code block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote. Importantly, in the actual markdown text this footnote is written directly under the "Here's a sentence with at footnote".

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight not supported in github

I need to highlight these == very important words ==.

I need to highlight these <mark> very important words </mark>.

<span style="background-color: #FFFF00"> This text is highlighted with the html span tags. </span>

### Subscript not supported in github

H~2~O this implementaion of markdown does not support sub-script

H<sub>2</sub>0  you can use html tags to get there
### Superscript not supported in github

X^2^ this implementaion of markdown does not support super-script

X<sup>2</sup>  you can use html tags though


That is so funny :joy: 😄 The last smily face only appears in html render ie git-pages....

<img src="UC-horz-rgb.png" alt="uc horizontal logo" width="200" height="75">

### The image is linked with html tags and should appear above, could you place the image in another folder and create a path to it?

