Cordova Toast plugin for Android
================================
For displaying a short message for a few seconds at the bottom of the screen.
![Screenshot](http://richardgilmour.co.uk/wp-content/uploads/2013/01/Screenshot_2013-01-08-19-29-18-e1357674008898.png)

This has only been tested with Cordova 2.3rc2. 

###Usage
1 - Add javascript file to project

2 - Add java file to com.phonegap.plugin.toast package

3 - to *config.xml* add 
`<plugin name="Toast" value="com.phonegap.plugin.toast.Toast"/>`

4 - Use the following commands:
`window.plugins.toast.longToast('string');`
`window.plugins.toast.shortToast('string');`

License
=======
Copyright 2013 Richard Gilmour - http://richardgilmour.co.uk/
You are free to do whatever you want with these files. If something goes wrong, it's not my fault...
