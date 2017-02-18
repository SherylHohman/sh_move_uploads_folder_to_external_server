This plugin moves files from "uploads" folder on main wordpress website
To an "uploads" folder on an external server.

Hmm.. when upload new files, will they still always go to the wp-defined uploads folder,
then simply copy themsselves (via this plugin) over to the ftp server ?? (and then self-delete from wordpress site)
If this is so, then do the links in the db also need to be immediately updated ??
And, does a redirect for each newly uploaded file need to be 301 defined in the .htaccess folder (probably as single wild card)??
UGH. This plugin may not be the holy grail I intended !!

For my part, I defined constants for the (external) ftp uploads server that are to be manually set in wp-config.php
The original version had username and password values hard-coded directly in the plugin file.
Security Issue!!

I also renamed the plugin to something more descriptive, and memorable.

CREDITS:
Forked from: https://github.com/pontusab/wp-ftp-media-library
**just proof of concept to answer question on wpse**
Answer question http://wordpress.stackexchange.com/questions/74180/upload-images-to-remote-server/78129#78129
