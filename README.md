RadioPi
===========

A simple media player for the Raspberry Pi for streaming audio as FM , written in Python 3 for raspbian.

This has been done by hacking the RasPyPlayer to accomodate the FM streaming capabilities

http://radiopi.in


Mount SMB Folder at /media/nas
--------------------------------

Add the following line in your /etc/rc.local:

    mount -t cifs //nashostname/nasvolume/ -o username=<smb username>,password=<smb password> /media/nas -o iocharset=utf8

First launch of Radio-Pi
---------------------------

You need to install python3 

sudo apt-get install python3
sudo apt-get install python-dev
sudo apt-get install pythonTk
to run it
Python3 RasPyPlayer 

As of now we can stream only wav files in 16bit format




