# How to enable debugging for android apps ? Xposed Way?


it is necessary to do debugging of the app to know how methods are being called in android .

To do debugging im using :-

    Poco f1 device with pie
    Rooted with magisk
    Xposed installed
    App Debuggable (module can be found in xposed modules ) 

after u install the module enable it and select which apps to be debuggable

in App Debuggable app .

Note : Afer u select the app to be debugged you have to restart the phone to take the changes effect .

After u can check it by using “adb jdwp” command

and also adb shell ps -e | grep <package-name>

Now u get the pid of the app

the use andbug or jdb to debugg the app 
