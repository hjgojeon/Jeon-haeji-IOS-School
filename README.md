### hj-program
---------------------------
# Syntax guide
## Heders

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

## Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## Lists
### Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
 
## Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   
## Images
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

## Links
http://github.com - automatic!
[GitHub](http://github.com)



## Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.

## Inline code
I think you should use an
`<addr>` element here instead.

---------------------------------
# Syntax highlighting

## Here’s an example of how you can use syntax highlighting with GitHub Flavored Markdown:
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
## you can also simply indent your code by four spaces:
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    
## Here’s an example of Python code without syntax highlighting:
def foo():
    if not bar:
        return True
        
## Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Tables
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

## SHA references
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

## Issue references within a repository
#1
mojombo#1
mojombo/github-flavored-markdown#1

## Username @mentions
Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

## Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.

## Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

## Emoji
GitHub supports emoji! :sparkles: :camel: :boom:

To see a list of every image we support, check out the Emoji Cheat Sheet.




