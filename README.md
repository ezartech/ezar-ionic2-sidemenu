# ezar-sidemenu
<work in progress>
An example project demonstrating the use of the ezAR VideoOverlay plugin with the
ionic2 sidemenu project template. 

This is an early checkin. To build the project
1. install ionic 2
2. clone this project
3. add the ezAR VideoOverlay plugin to the project
4. add either the iOS platform, the android platform or both to the project
5. build the project, install on your device and launch it.

Known issues:
1) The VideoOverlay automatically adjusts the size of the Ionic (Cordova) webview to 
match the size of the camera view. The next update of the VideoOverlay plugin will include
a configuration option to preclude the webview resizing. The webview resizing is typically a non-issues
if your app runs in full-screen mode. 

Tips:
1. See modifications I made to the following files: app.components.ts, app.scss, page1.html, page1.scss