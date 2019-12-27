# basic text format
### italics
- use * for *italic*
- use double * for **bold**
- escape char \

line breaks work as normal 

> but for an extra line break \ this works 
> you can also use two  to create a line break

\# will show headers 
the more \# the smaller the ### header

# blockquotes
use a greater sign followed by a space

> this is a blockquote
>
>> this is a nested blockquote

# lists 
## unordered list
unordered list - * + or - as marker
* one
* two 
* three

## ordered list
ordered list number. or number)
1. point
2. point 
3. point

# links
## inline link
link text is enclosed in square brackets
[text](www.google.com)
inline links have URL enclosed by ()

urls can be converted to links by enclosing in <>

## reference style links
[Hurricane][1] Erika was the strongest and longest-lasting tropical cyclone in the 1997 Atlantic [hurricane][1] season. Both these links point at the same source.
[1]:https://goo.gl/YEEHP0

# images
image links start with an exclamation
![image text](https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png)
\![image text](https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png)

- ![1](https://commonmark.org/help/images/favicon.png)

![LOGO][1]
[1]:https://commonmark.org/help/images/favicon.png "CC LICENSED"

## code
to wrap inline code use backtick 'code'

code blocks use indent space x 4 or three backticks
    
    code goes here 

        more code
    

this is regular text after code block

## nested lists

indent sublist items by four spaces
* item
    1. sub item one
    2. sub item two
* other item