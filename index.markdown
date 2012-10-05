<link href="http://kevinburke.bitbucket.org/markdowncss/markdown.css" rel="stylesheet"></link>

#Hi! 

This is my personal collection of common (but not so common to remember) cmd/bash commands, feel free to copy and paste. 

CSS - [Kenvin Burke's markdown css](http://kevinburke.bitbucket.org/markdowncss/) 

Licence - [WTFPL](http://sam.zoy.org/wtfpl/) 

Syntax Reference - [http://daringfireball.net/projects/markdown/syntax#link](http://daringfireball.net/projects/markdown/syntax) 

Contact - tuxtor at shekalug dot org

##Bash cheats
Search recursively over files into a directory 

	find . -type f -exec grep '<String or regepx>' {} \; -print 

Set default group for vsftpd uploads (set the sticky bit and all files will be owned by the dir owner) 

	chmod g+s 

Default mask for vsftpd files at (local umask) 

	/etc/vsftpd.conf 

Allow directory listing on apache using .htaccess file 

	cat "Options +Indexes" >> $SITE_DIR/.htaccess 
***** 
##Sar common options
* -b I/O stadistics 
* -B paging stadistics 
* -C read comments from datafile 
* -d read activity from block device 
* -i select data between a defined interval
* -m CPU speed
* -n Network speed
  DEV 
*  -p cpu|ALL
*  -q tareas en cola
*  -r memoria (utilizacion)
*  -R memory stadistics
*  -u cpu utilization
*  -t original local time
*  -v kernel stadistics
*  -w task creation, task switching
*  -W swapping stadistics
*  -y tty device activity

***** 

##VCS cheats
Add an alias for git add, git commit and git push (one-shot git!) 

	git config --global alias.ons '!git add -A && git commit && git push'
	git ons
***** 

The end :)
