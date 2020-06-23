---
title: "First Test Post: Single, Wide Layout"
author: Math Vault
layout: single
permalink: /first-post/
category: Posts
classes: wide
toc: true
sidebar: 
  - title: "Navigational Menu"
    image: /BLM.jpg
    text: "Everything can be found here." 
  - title: "Instruction"
    image: /Redditbots.png
    text: "Read everything carefully before giving up." 
    
  - nav: main
---

A **first post**. Exciting!

Center-align text with `{: .text-center}`
{: .text-center}

Right-align text with `{: .text-right}`
{: .text-right}

Inline math works as usual: $E=mc^2$

## Markdown Reference Sheet

### Headings with `#`

# Heading 1
## Heading 2 with the `{: .text-right}` Tag
{: .text-right}

### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

### Text Ornaments

*Bold* with `*` or `_`

**Italic** with `**` or `__`

`code` with `

[link](https://mathvault.ca) with \[link\](your-url)

Link to [**anchor**](#text-ornaments) is fine too.

To turn URL (such as <https://mathvault.ca>) into link, use `<>`.

~~strikethrough~~ with `~~`

Emoji such as :smiley_cat: are supported with `:smiley_cat:`. See [cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) for more (might not work outside GitHub)

Horizontal rule with `---`

---

Multiline codes with three backticks (followed by code's language if applicable)

```python
s = "Python syntax highlighting"
print s
```

## Line break

Use an empty line to break paragraphs

To break a line without breakihg the paragraph, add double spaces after content

## Special Characters

To typeset special characters (such as \]), append `\` before it.

## Lists

* Unordered list with `* `
* Nested list with indent
  * Like this
  * And this

1. Ordered list with `1. `
1. Let the numbering take care of itself
1. Nesting is also possible with indent
   1. Like this
   1. And this
   
- [ ] For checklist, use `- [ ]`
- [x] For checked item, use `- [x]`
  - [ ] Nesting is possible as well
  - [x] Like this
   
## Images

Like link. Just append a `!` before everything.

![Mathematician](/BLM.jpg)

Default (Left-align)

![Mathematician](/Redditbots.png)

**Center align** by suffixing `{: .align-center}`

![Mathematician](/Redditbots.png){: .align-center}


**Right align** by suffixing `{: .align-right}`

![Mathematician](/Redditbots.png){: .align-right}

## Blockquote with `> `

> "I'm a mathematician. And you're a technician."
> > Nesting blockquote can be fun
> > > And the third-level gets even "funner"!

## Table

Use `-` to draw horizontal line, and `|` to draw vertical line.

`Description | Quantity | Price`   
`----------- | -------- | -----`   
`Mushies | 4 | $1.99`  
`Pumpkin | 1 | $9.97`  
`Philips Electric Razor | 2 | $29.99`

Description | Quantity | Price
----------- | -------- | -----
Mushies | 4 | $1.99
Pumpkin | 1 | $9.97
Philips Electric Razor | 2 | $29.99 

## Raw HTML

### Description List

```
<dl>
  <dt>Cat</dt>
  <dd>A feline animal. Similar to lion.</dd>

  <dt>Dog</dt>
  <dd>A canine animal. Sometimes not very friendly.</dd>
</dl>
```

<dl>
  <dt>Cat</dt>
  <dd>A feline animal. Similar to lion.</dd>

  <dt>Dog</dt>
  <dd>A canine animal. Sometimes not very friendly.</dd>
</dl>

### Alternatively-aligned paragraphs

Using `p` tag with `text-align:right`

<p style="text-align:right;">A right-aligned paragraph. Not possible in native Markdown, but still possible with HTML!</p>

### Superscript and Subscript

<h3 style="text-align:center;">E<sub>nergy</sub> = mc<sup>123456780</sup>!</h3>

That's it! Class dismissed!


