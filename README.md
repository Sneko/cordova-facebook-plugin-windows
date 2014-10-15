Presentation
===============================

This Cordova plugin use the same syntax that :
https://github.com/Wizcorp/phonegap-facebook-plugin

So you can use it with mine, there will be no interference.

It permit to use Facebook dialogs on Windows platform (version 8.1 minimum). It's a great alternative to FacebookSDK.net which haven't the capacity to display the Facebook UI (requesting, sharing...).

**WARNING! Some disadvantages exist**


**- This pluging uses the new Windows webview feature, and it's only available for Windows 8.1/Windows Phone 8.1 minimum**

**- Because webviews, you need to put a page on a website to mediate between your Windows app and Facebook servers**

**- To communicate between your app and the website page inside the webview, Microsoft are requiring you use HTTPS (secure connection), so you must have a SSL license (cost minimum 7 dollars/year).**

Setup
===============================

## On your website

Upload the "website" directory on your server. Remember, you need to have a SSL connection!


## In app

In your Cordova project, put the "/windows/facebookConnectPlugin.js" in the "www" directory into your Windows app.

