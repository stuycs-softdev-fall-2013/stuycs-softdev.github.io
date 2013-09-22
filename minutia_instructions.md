---
layout: default
---

Instructions for writing minutia
================================

## Refernence

[Markdown Reference](http://daringfireball.net/projects/markdown/syntax)

[GitHub Markdown Info](https://help.github.com/articles/github-flavored-markdown)

**You must follow these instructions exactly, including things like filename convensions**


1. git pull the in the stuycs-softdev.github.io repository.
2. go into the posts directory and create the new file or edit the existing one.
3. It should be named using the form *year-month-day-pd#-title.md* or *year-month-day-pd#-title.html* . Use the extension .html if you're writing html and .md if you are using markdown. For example, a period 7 minutia posting might be named **2013-09-23-pd7-this_is_the_title.md**

Make sure the file has the following on top:

> \-\-\-<br>
> layout: THELAYOUT<br>
> title: whatever the title is<br>
> \-\-\-

Where **THELAYOUT** is **minutia-6** or **minutia-7**.

Then: 

1. git add the post file
2. git commit it
3. git push

**Please make sure that the post appears (it could take a couple of minutes. If not, you'll have to figure out what's wrong with the markup**

**You can install jekyll to test things locally**