<link href="http://kevinburke.bitbucket.org/markdowncss/markdown.css" rel="stylesheet"></link>

This is my personal collection of common (but not so common to remember) cmd/bash commands, feel free to copy and paste. 

CSS - [Kenvin Burke's markdown css](http://kevinburke.bitbucket.org/markdowncss/) 

Licence - [WTFPL](http://sam.zoy.org/wtfpl/) 

Syntax Reference - [http://daringfireball.net/projects/markdown/syntax#link](http://daringfireball.net/projects/markdown/syntax#link) 

Bash cheats
===========
Search recursively over files into a directory 

	find . -type f -exec grep '<String or regepx>' {} \; -print 
***** 
VCS cheats
==========
Add an alias for git add, git commit and git push (one-shot git!) 

	git config --global alias.ons '!git add -A && git commit && git push'

***** 
The end :)
