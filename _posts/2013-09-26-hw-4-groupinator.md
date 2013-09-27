---
layout: hw
title: hw 4 - Groupinator
date: 2013-09-27 7:30:00
---

### The program

Write a python program **groupinator.py** that will break up the classes into groups of 4 (with groups being comprised of people in the same class).

You can grab a list of students from the classcode repository under resources/groupinator.


### Some hints to get you started

First you should read a file. In python we can do that with:

> lines=open(filname).readlines()

where filename is a string with the filename. The variable **lines** will now be a list where each element is a line from the file.

You'll probably want to get rid of the newline at the end of each line:

> newlines = \[\]<p/>
> for l in lines:
>   newlines = l.strip() # strip removes the trailing newline

Notice that each line is 4 pieces of info seperated by commas (comma delimited values or csv). You can use the string **split** method to convert each line to a list if you want. For example:

> l = "one,two,three,four".split(",")

will leave you with l=\['one','two','three','four'\]

The string **join** method does the reverse:

> s = ":".join(\['one','two','three'\]

will give you s = "one:two:three"

You might or might not need these.

You can also use the python built in **csv** module - you should look
that up online.

You might want to sort or jumble the data. Search on python sort and
look at the python random module.

### The output

Groups should be numberd 1 to 16 (1-8 for period 6 and 9-16 for period 7) so your output might look like this:

> 1,last,first<p/>
> 1,last,first<p/>
> 1,last,first<p/>
> 1,last,first<p/>
> 2,last,first<p/>
> 2,last,first<p/>
> 2,last,first<p/>
> 2,last,first<p/>

etc. 

### Where it goes

Place this  under your submissions folder with the name "groupinator.py" and also put the data file in that directory

### Final important note

I think you should be able to handle this but you will need to look up a number of python specifics. It's **very important that you keep me in the communication loop** on this assignment. If I'm asking too much of you, it's important that I know that I've left something out in your preparation and I have adjust.


