lets try some markdown syntaxs!
first lets try links! for the sole reason that a website is explaining this to me a lot easier.

# Links
>This is [an example](http://example.com/ "Title") inline link.
>
>[This link](http://example.net/) has no title attribute.
  
trying these sample codes in the "preview" section was really helpful as i didnt understand what a title attribute was. Its the box that appears when hovering over the link

# Relative paths
>If you’re referring to a local resource on the same server, you can use relative paths
>
>See my [About](/about/) page for details.

# Reference-Style Links
>Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:
>
>This is [an example][id] reference-style link.
>You can optionally use a space to separate the sets of brackets:
>
>This is [an example] [id] reference-style link.
>Then, anywhere in the document, you define your link label like this, on a line by itself:
>
>[id]: http://example.com/  "Optional Title Here"

with this knowledge i will create a reference link to the site i'm learning from, which is [fireball][]

it seems that "link definitions" have to be on a line away from the previous

[Fireball]: https://daringfireball.net/projects/markdown/syntax#link "Fireball Link" 



# HEADERS
Lets try Headers Here as these can be very useful to go back and add to my link section
>Markdown supports two styles of headers, Setext and atx.
>
>Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:
>
>This is an H1
>=============
>
>This is an H2
>-------------
>Any number of underlining =’s or -’s will work.
>
>Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:
>
># This is an H1
>
>## This is an H2
>
>###### This is an H6

the easiest method for me is using the #

notes (using list): 
*  does not need an empty line before or after it
*   must be a space after the #

# Block Quotes
very simple, just add a > and Done!

much needed to cleanup the previous sections


#Emphasis
>Some of these words *are emphasized*.
>Some of these words _are emphasized also_.
>
>Use two asterisks for **strong emphasis**.
>Or, if you prefer, __use two underscores instead__.

Notes:
*  simply a * (or two if going for the strong version) before and after the target
*  its apparent even in the edit tab
