# Examples #

It's very easy to make some words **bold** and other words *italic* with Markdown. 
You can even [link to Google!](http://google.com)


# Syntax #

# Headers #
Uses the # - for each step up add another.
Must have # before and space then space after and #

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

# Spaces and Tabs #
Regular space: &nbsp;
Two spaces gap: &ensp;
Four spaces gap: &emsp;

# Emphasis #
Uses * and _ for italics
Uses ** and __ for bold

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

# Strikethrough #
Use two tilda ~ around the content to be crossed out

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

# Lists #

Unordered
Each item starts with a * and a space
Sublists start with a space then a * then another space

* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
Ordered 
Each item starts with 1. and a space
Sublists start with a space followed by 1. and another space

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
# Images #
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

# Links #
http://github.com - automatic!
[GitHub](http://github.com)

# Blockquotes #
As Kanye West said:

> We're living the future so
> the present is our past.

# Inline Code #
I think you should use an
`<addr>` element here instead.

# Syntax Code Highlighting #
Either use ``` or indent four spaces

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Fancy Formatting ##

# Tasklists #
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

# Tables #
Create using --- to divide elements and have a | between each collumn element

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

# SHA-1 Hash Reference #
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

# Issue Referencing #
Will automatically link to issue if it exists.

#1
mojombo#1
mojombo/github-flavored-markdown#1

# @Mentions #
Using @ followed by GitHub username you alert another user that you need their help or input on something.

# Autolink URLS #
URLS will automatically convert to clickable links in GitHub

# Emojis #
Github supports an array of Emojis. See [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

