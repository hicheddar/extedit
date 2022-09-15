# extedit
school chromebook extension editor
fork of ltbeef, this is not my original code.

> ### use at your OWN RISK
> please use this exploit at your own risk. i do not hold responsibility for anything after you use this.

uses chrome API to toggle extensions.
currently a loophole

# install
extedit uses a bookmarklet
paste this code into the url box of a new bookmark
```js
javascript:fetch("https://github.com/hicheddar/extedit/blob/main/mainexploit.js/").then(data=>{data.text().then(text=>{eval(text)})});)
```
to enable, go to a page and click the bookmarklet.
if you are taken to a 404 page, click it again and the menu will open.

# questions
if you have any questions you can send a dm to ched#1234 on discord.
