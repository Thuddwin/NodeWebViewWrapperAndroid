# WebViewWrapperAndroid-
This repo is used to call the NodeWirelessThermo, which is a web app using Bootstrap 5, jQuery, vanilla javascript, Node.js and express.  NodeWirelessThermo is the Server.<br/><br/>
This project, WebViewWrapperAndroid, is a Client, but any Device with a Browser can be a Client. This project, however, allows the app to run in Full Screen mode, which is difficult, if not impossible to do, on Android Tablets using standalone Browsers.  It is very minimal in that it is an Android application that only contains a WebView object.  The WebView object URL is hard-coded to: http://192.168.1.14:4000.  Therefore, a router must be setup with Address Reservation to force the Server to have that URL (minus the 4000).

This app can be side-loaded from my Google Drive and is called full-screen.apk.

The hard-coded URL can be changed to any other URL.
Will rename this repo to WebViewWrapperAndroid.
