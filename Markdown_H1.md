Heading
=======

Sub-heading
-----------

## Hi RADWAN : This is The New Feature Branch

## Hi RADWAN : This is Feature Branch#3

# Alternative heading #

Paragraphs are separated 
by a blank line.

Two spaces at the end of a line  
produce a line break.

---

Text attributes _italic_, **bold**, `monospace`.

Horizontal rule:

---

Bullet lists nested within numbered list:

  1. fruits
     * apple
     * banana
  2. vegetables
     - carrot
     - broccoli
		 
---

A [link](http://example.com).

![Image](Icon-pictures.png "icon")

> Markdown uses email-style
characters for blockquoting.
>
> Multiple paragraphs need to be prepended individually.

Most inline <abbr title="Hypertext Markup Language">HTML</abbr> is supported.


---

**Add Hyperlink**
to add Hyperlink use this format : `[Map Group Filter Page]()`

e.g : See [Map Group Filter Page]()

---

**Add Image**

to add an Image path , you have three methods :
1. add reference like : `![](image_file_name.png)`
e.g :
![](portainer-architecture-detailed.png)

---
2. add reference like : `![ref1]` where `![ref1]` is a reference listed at the end of **MD** File.
e.g :

![ref2]

---
3. add reference like : `![Image](Icon-pictures.png "icon")` . e.g:

![Image](Icon-pictures.png "icon")

---


## Alignment


| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

---
Characters can be grouped by putting them inside square brackets.

| Pattern | Meaning |
| ------- | ------- |
| [xyz]	| Match the character x,y or z. |
| [a-z]	| Match any of the characters between a and z. |
| [^abc],[^0-9]	| A “^” caret at the beginning denotes “not.” Here the characters other than a,b,c is matched. |
| [+*?.]	 | For your information most special characters have no meaning inside the square brackets. This particular expression matches any of the special characters within the square brackets. |

***
You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

***
## Syntax Highlighting

Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
___

## Footnotes

Footnotes allow you to add notes and references without cluttering the body of the document. When you create a footnote, a superscript number with a link appears where you added the footnote reference. Readers can click the link to jump to the content of the footnote at the bottom of the page.

To create a footnote reference, add a caret and an identifier inside brackets ([^1]). Identifiers can be numbers or words, but they can’t contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.

Add the footnote using another caret and number inside brackets with a colon and text ([^1]: My footnote.). You don’t have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


---

## Definition Lists {#custom-id}

Some Markdown processors allow you to create definition lists of terms and their corresponding definitions. To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

***
## Strikethrough
~~The world is flat.~~ We now know that the world is round.

---
## Task Lists

Task lists (also referred to as checklists and todo lists) allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

***
## Highlight
This isn’t common, but some Markdown processors allow you to highlight text. The result looks like this. To highlight words, use two equal signs (==) before and after the words.

I need to highlight these ==very important words== .

***
## Subscript

This isn’t common, but some Markdown processors allow you to use subscript to position one or more characters slightly below the normal line of type. To create a subscript, use one tilde symbol (~) before and after the characters.

H~2~O

X^2^

***
## Using Emoji Shortcodes

Some Markdown applications allow you to insert emoji by typing emoji shortcodes. These begin and end with a colon and include the name of an emoji.

Gone camping! :tent: Be back soon.

That is so funny! :joy:

***
***



___
Copyright © 1988, 2015, Oracle and/or its affiliates. All rights reserved. 

[ref1]: lvm-cheatsheet.png
[ref2]: Icon-pictures.png
