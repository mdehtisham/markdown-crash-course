# Markdown Crash Course
### This repository contains a crash course about mark down.

<!-- Headings -->
## Heading
Headings can be written using # sign in the beginning of a sentence then a space and then write the sentence. There are six levels of heading in the markdown like HTML has.  
If you want heading 1 then use # only one time.  
If you want heading 6 then use ###### six times.
Example:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Line Break in markdown -->
## Line Break
Line break can be added using double space or \ (backslash) in the end.  
Example:  
I am first sentence.  
I am second sentence. \
I am third sentence.

<!-- Italics -->
## Italics
Any text can be converted into Italics by adding *(asterisk) or _ (underscore) in the beginning and in the end of the text.  
Example:

*This Text* is Italic.  
_I am also_ Italic.

<!-- Strong -->
## Strong
Strong text can be written using double * or double _.  
Example:  
**strong text using double asterisk**  
__strong text using double underscore__

<!-- Strike Through -->
## Strike Through
Double ~(tilde) is used to strike through any text.  
Example:  
~~double tilde~~ is used to strike through.

<!-- Horizontal Rule -->
## Horizontal Rule
Triple _ (underscore) or Triple -(hyphen/dash) is used to create a horizontal rule.  
Example:
___

<!-- Escape Character -->
## Escape Character
Back Slash is used to escape characters.  
Example:  
*\*Italic\**

<!-- Blockquotes -->
## Blockquotes
Greater than (>) is used to add blockquotes.  
Example:  
> This is a Quote.  

<!-- Links -->
## Links
The text you want to add as a link goes into square bracket and the url goes into parenthesis.  
Example:  
[Github](www.github.com)

### Add Title to a link  
Create a link the add the space in parenthesis and add the title in double quotes ("").  
Example:  
<!-- [website text](url "title")   -->
[Github](www.github.com "github")  

## Unordered List
Unordered list can be created by just added * infront of each item, and each items should be in new line.  
Example:  
* Item 1
* Item 2
* Item 3  

## Nested Items  
Nested list can be created by adding single tab before an item.

* Item 1
* Item 2
* Item 3
    * Nested level 2
        * Nested level 3
* Item 4

## Ordered List  
Ordered list can be created by adding 1. before each item, each item should be in new line.  
1. Item 1
1. Item 2
1. Item 3

## Inline Codeblock
Use `` (backticks) in beginning and end to write inline code block.  
`<p> This is a paragraph</p>`  

## Images
Images can be added similarly we add links, with only one difference i.e. we just have to add ! mark before the link syntax.  
![Markdown Logo](https://markdown-here.com/img/icon256.png)


# Github Markdown
Github uses its own flavour of markdown.  

## Code Blocks
We use triple `(backticks) to create a code block.    
Example:
```
npm install 
npm start
etc
```
## Language specific code block
We use triple `(backticks) and add the name of language in the end of starting backticks.  
Example: 
```javascript
function sayHello(){
    console.log('hello world')
}
```

## Table
To see the syntax to table go to raw tab and see it.

| Name | Email    |
|------|--------  |
|John  |john@g.com|
|Jane  |jane@g.com|

## Task List
Add te * (asterisk) before each item. After that add [x] for completed tasks and [ ] for incomplete task.  
* [x] item 1
* [ ] item 2
* [x] item 3