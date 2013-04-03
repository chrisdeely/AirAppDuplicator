AirAppDuplicator 1.0.0
======================
[Click here to download the installer](https://github.com/downloads/chrisdeely/AirAppDuplicator/AIRAppDuplicator.air)

This is a very simple Adobe AIR application which will allow you to easily 
make duplicate installations of any AIR application.

Why would you want to do this?  Well... that's up to you I guess. I have 
used a few AIR apps where I wish I could open multiple windows at once. Now 
I can.

I have had good reports of this working well for HipChat & TweetDeck clients.

On Windows 7/8 you may need to run the app as Administrator in order for it to have proper system access.
- Navigate to C:\Program Files\AIRAppDuplicator
- Right-click on AIRAppDuplicator.exe
- Select 'Run as Administrator'

Tech Notes
----------

The source is quite simple.  All you have to do is copy the application 
directory to a new folder then edit the application descriptor and assign a 
new 'application ID'.

The downside to this is that the new installation will have its own 
application storage directory.  This means that settings may not be shared 
between different copies.

This hasn't been widely tested. It has worked on every app I've tried so far.
If you have problems contact me on Twitter @chrisdeely

Adobe AIR and associated logos are registered trademarks of Adobe Systems Inc.

...or so I assume
