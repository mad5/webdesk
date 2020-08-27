#webdesk

Active Desktop was a function of the Microsoft Windows operating system to 
display web pages directly on the desktop.

Since many years I don't use Windows anymore but switched to Lubuntu. 
But what I always missed was the active desktop from back then.


##  extra tools you need

Download from:

https://gist.github.com/cat-in-136/96ee8e96e81e0cc763d085ed697fe193

Compile with:
 
	gcc toggle-decorations.c -Wall -o toggle-decorations `pkg-config --cflags --libs x11`
 

wmctrl to set window into back and make it full size
 
	sudo apt install wmctrl
	
chromium-browser

	sudo apt install chromium-browser
 
 ## open external website
 
 start the script 
 
	runsmall
	
inside you can set the destination-website e.g. https://www.google.com
and set the title of your destination-page e.g. "Google - Mozzila Firefox"

## use local webserver

install php

	sudo apt install php
	
put your website into docroot-folder

	mkdir docroot
	touch docroot/run.php
	
