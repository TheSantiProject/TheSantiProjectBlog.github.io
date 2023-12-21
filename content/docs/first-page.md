---
title: Demo Page
type: docs
prev: /
next: docs/folder/
---

A simple demo page.

HEADERS LISTS IMAGES
  # This is an <h1> tag
## This is an <h2> tag ###### This is an <h6> tag
EMPHASIS
Unordered
Ordered
BACKSLASH ESCAPES
LINKS
BLOCKQUOTES
Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formatting syntax.
Markdown provides backslash escapes for the following characters:
![GitHub Logo](/images/logo.png) Format: ![Alt Text](url)
 * Item 1
* Item 2
* Item 2a * Item 2b
   *This text will be italic* _This will also be italic_
**This text will be bold** __This will also be bold__
*You **can** combine them*
1. Item 1 2. Item 2 3. Item 3
* Item 3a * Item 3b
http://github.com - automatic! [GitHub](http://github.com)
As Grace Hopper said:
> I’ve always been more interested > in the future than in the past.
As Grace Hopper said:
I've always been more interested in the future than in the past.
\*literal asterisks\*
*literal asterisks*
\ backslash
` backtick
* asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hashmark
+ plus sign
- minus sign (hyphen) . dot
! exclamation mark
  
 
                                                                                                
FENCED CODE BLOCKS
Markdown coverts text with four leading spaces into a code block; with GFM you can wrap your code with ``` to create a code block without the leading spaces. Add an optional language identifier and your code will get syntax highlighting.
```javascript
function test() {
 console.log("look ma’, no spaces");
}
```
 function test() {
console.log("look ma’, no spaces"); }
TASK LISTS
TABLES
You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe | :
- [x] this is a complete item
- [ ] this is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
this is a complete item this is an incomplete item
@mentions, #refs, links, formatting, and tags supported
list syntax required (any unordered or ordered list supported)
 #1
github-flavored-markdown#1
defunkt/github-flavored-markdown#1
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2
First Header
Second Header
Content cell 1
Content cell 2
Content column 1
Content column 2