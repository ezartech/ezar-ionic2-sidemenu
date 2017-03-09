# ezar-sidemenu
<work in progress>
An example project demonstrating the use of the ezAR VideoOverlay plugin with the
ionic2 sidemenu project template. 

This is an early checkin. To build the project
1. install ionic 2
2. clone this project
3. add dependent modules to the project 
    npm install
4. add the ezAR VideoOverlay plugin to the project
    ionic plugin add <path2plugins>/plugins/com.ezartech.ezar.videooverlay
5. add either the iOS platform, the android platform or both to the project
    ionic platform add android
    ionic platform add ios
6. build the project, install on your device and launch it. 
    ionic build <platform>

Tips:
1. See modifications I made to the following files: app.components.ts, app.scss, page1.html, page1.scss