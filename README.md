# Enable-GPS

A tutorial to enable location service directly (like in google maps app).

Add the library in build.gradle
> compile 'com.google.android.gms:play-services:8.4.0'

Connect to google api client (connectToApi() method)

Once it is connected, check if location is on or not and show a dialog to switch it on.

Get the result of the user in onActivityResult()
