Code4Lib 2016 IRC Quick Start Guide
===================================

The [official code4lib IRC page](http://code4lib.org/irc/). is very helpful and contains more comprehensive info. This guide will just get you up and running ASAP. 

Quick and Easy
--------------
Go to [http://webchat.freenode.net/](http://webchat.freenode.net/)


Step 1: Client
--------------------

Windows: [HexChat](https://hexchat.github.io/)
Mac: http://colloquy.info/
Linux: xchat: sudo apt-get install xchat

Or irssi: https://irssi.org/

*Note: the commands below are for irssi or similar clients. The GUI clients should guide you through these steps. 

Step 2: Connect
-----------------------------
	
`/connect chat.freenode.net`

Step 3: Nick(name)
------------------
	
Pick a nick. This is how you will appear to others.
`/nick mycoolname`

Do you want to save your nick and use it again in the future? Of course you do! You'll need to register it. 
`/msg nickserv register YourPasswordHere you@example.com`

*Note: Never ever ever use the same password for IRC that you use elsewhere. IRC traffic is plaintext. If your client offers SSL, use it! For irssi, see [Code Portland's irssi, ssl, and freenode](https://codeportland.com/irssi/).

Next, go to the email address you used and look for a message from <noreply.support@freenode.net>. Check your spam folder. Get the text from the message and paste it into the client. 
`/msg NickServ VERIFY REGISTER your_nick ............`
	
Step 4: Join
------------
Join the channel
`/join #code4lib`

Step 5: Chat
------------
Hang out and observe or jump right in and say 'hi'. Be sure to read the [official code4lib IRC page](http://code4lib.org/irc/). 

Learn about Zoia at the [Code4Lib Wiki page on Zoia](http://wiki.code4lib.org/Zoia_or_the_Code4Lib_IRC_bot).

You'll see lots of messages about users joining and leaving the channel. These can take up a lot of space, so you may want to ignore them.
`/ignore -channels #channel * JOINS PARTS QUITS NICKS`
`/save`

Step 6: Leave
-------------
`/part` will make you leave the channel
`/quit` will close the client 

Step 7: Return
--------------
Returning after you've closed the connection. 
`/connect chat.freenode.net`
You'll need to tell the NickServ who you are
`/msg NickServ IDENTIFY YourPasswordHere`

This should get you started. Again, be sure to read the [official code4lib IRC page](http://code4lib.org/irc/). It has links to everything you'll need to know.