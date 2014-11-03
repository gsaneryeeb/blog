---
layout: page
title: Very Simple Markdown Synx
---

##{{ page.title }}



### \# ## ### Headers

***

\***,---,___ ;horizontal

***

* \* ,+,-, 1. Lists

1. 1\. Lists

***

> \> Blockquotes

***

Code Blocks

    4x space code blocks

***

text `` `There is a literal backtick (`) here. ` `` text

***

[ \[link\](url "tip")](www.google.com "google")

***

Reference-style links:[\[link1\]\[1\]][1] and [\[link2\]\[2\]][2] 

...

\[1\]: www.google.com "google"

\[2\]: www.apple.com "apple"

[1]: www.google.com "google"
[2]: www.apple.com "apple"

***

*\*italic\**

**\**bold**\**

***

![pic text](http://www.daimler.com/Projects/c2c/channel/images/998886_1945816_325_110_mb_passcars.jpg "Benz")

    \!\[pic text\](http://www.daimler.com/Projects/c2c/channel/images/998886_1945816_325_110_mb_passcars.jpg "Benz")



***

![pic text][1]

![pic text][2]


    \!\[pic text\]\[1\]

    \!\[pic text\]\[2\]

...

    \[1]:http://www.daimler.com/Projects/c2c/channel/images/998886_1945816_325_110_mb_passcars.jpg "benz"
    \[2]:http://www.daimler.com/Projects/c2c/channel/images/998887_1945818_325_110_smart.jpg "smart"





[1]:http://www.daimler.com/Projects/c2c/channel/images/998886_1945816_325_110_mb_passcars.jpg "benz"
[2]:http://www.daimler.com/Projects/c2c/channel/images/998887_1945818_325_110_smart.jpg "smart"



{{ page.date | data_to_string}}
