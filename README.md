# phonegap-embed-vimeo
This is a “hello world” phonegap application that is ready for testing and further development.
It demonstates the basic use of an embedded vimeo video using the embed code directly from vimeo.
Note it contains a config.xml file, but the file should be moved inside the www directory for uploading to phonegap build

How to use
----------
Create a new phonegap project using Phonegap cli or desktop app 
Replace the www directory with this repository.
Replace the config.xml file with this config file
Replace the reference to the video file with your own
```
https://player.vimeo.com/video/163170188?color=fcfcfc&title=0&byline=0&portrait=0'
````

More information
----------
This repository demos the basic use of an embedded video in a phonegap app.
For this to work the following line must be added to the config.xml file
```
<allow-navigation href="*://*vimeo.com/*" />
```
This allows the app to communicate with any domain, sub domain and sub directory of vimeo.

Embedding from Vimeo
----------
For a full range of customisation options for embedding vimeo videos see the offical documentation
https://help.vimeo.com/hc/en-us/articles/224972808-Customizing-the-embedded-player
