---
title: "Practical Guide To Begin with Markdown"
date: 2019-03-13T18:56:52+01:00
draft: false
image: ""
categories: ["tutorials"]
tags: ["Blogging","Web"]
---
# Practical Guide To Begin with Markdown

Good morning/afternoon/evening, whatever time you are reading this post.

Friend, thank you for passing by.

As a short disclaimer, I want to let you know that I'm not a developer, simply someone who is curious about technology and willing to learn things by teaching them.

It sounds crazy right? 

Originally defined by Jean-Pol Martin in the 1980s, this method is focused on gathering knowledge and explain it to someone with your own words.

It increases your capacity of synthesis and forces you to go through diverse sources of information to produce the most accurate output.

This blog is based on the assertion that 'Learning by teaching' is a good method.

Of course, we are all curious minds thriving for freedom and knowledge, so I encourage you to find your own truth.

The tutorial of today is about having a practical guide to *"write with Markdown language"*

**We are going to explore 11 topics divided under 2 main sections :**

1. **_What is Markdown code?_** 
2.  **_How to use the syntax?_**


<!-- 1. Markdown
    1. Creation
    2. Purpose
    3. Fun Facts
2. Syntax
    1. Headers
    2. Horizontal Rules
    2. Emphasis
    3. Lists
        1. Unordered
        2. Ordered
    4. Images
    5. Links
    6. Blockquotes
    7. Backslash Escapes
    8. Inline code -->


---
## What Is Markdown Code?

### Creation
### Purpose
### Fun Facts

---
## How To Use The Syntax?

### Headers
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**
# H1
## H2
### H3
#### H4
##### H5
###### H6

### Horizontal rules

This markdown code allows to create break lines between sections.

```
___
---
***
```

**<span style="color:red"> On your blog, it renders the following: </span>**

___
---
***

### Emphasis
```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

### Lists
#### Unordered
```
* Item 1
* Item 2
 * Item 2a
 * Item 2b
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

* Item 1
* Item 2
 * Item 2a
 * Item 2b

#### Ordered
```
1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

1. Item 1
2. Item 2
3. Item 3
 * Item 3a
 * Item 3b

### Links
```
http://github.com - this is automatic!

[GitHub](http://github.com)
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

http://github.com - this is automatic!

[GitHub](http://github.com)

### Images
```
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

### Blockquotes
```
As Nelson Mandela said:

> Education is the most powerful weapon
> which you can use to change the world.
```
**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

As Nelson Mandela said:

> Education is the most powerful weapon
> which you can use to change the world.

### Backslash Escapes
```
\\ backslash
\* asterisk 
\` backtick
\* asterisk
\_ underscore
\{} curly braces
\[] square brackets
\() parentheses
\# hash mark
\+ plus sign
\- minus sign (hyphen)
\. dot
\! exclamation mark
```
**<span style="color:red"> With this trick, you're now able to use the following symbols on your blog: </span>**

* \\ (backslash)
* \* (asterisk)
* \` (backtick)
* \_ (underscore
* \{} (curly braces)
* \[] (square brackets)
* \() (parentheses)
* \# (hash mark)
* \+ (plus sign)
* \- (minus sign (hyphen))
* \. (dot)
* \! (exclamation mark)

### Inline Code
To indent code within your blog post, simply open with three times the backtick symbol and close with the same:

>\` \` \`

>Hello World!

>\` \` \`


**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

```
Hello World!
```

You can as well use only one backtick (\`) to indend small code in a line.

> In this example, \` \<section>\</section>\` should be wrapped as code.

**Renders to:**

In this example, `<section></section>` should be wrapped as code.

### Tables
```
| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```

**<span style="color:red"> On your blog, this markdown code renders the following: </span>**

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

##### Good To Know Before You Go

* If you want to add color to your text, add the following HTML to your markdown:

```
<span style="color:blue"> Blue </span>
```

Renders to: <span style="color:blue"> Blue </span>

* You can't underline text with Markdown. If necessary, do it with the following HTML:

```
<span style="text-decoration: underline;">This will be underlined.</span>
```

Renders to: <span style="text-decoration: underline;">This will be underlined.</span>

* GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features. However, these have not been treated in this article (yet?).

##### Sources:

* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#headers
* https://guides.github.com/features/mastering-markdown/
* https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf
* https://learn.netlify.com/en/cont/markdown/