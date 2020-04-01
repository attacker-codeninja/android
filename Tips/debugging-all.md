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

then use andbug or jdb to debugg the app 

** Note : xposed way make your phone more heat and apps behave wierdly ** 

## There is second way to do it wich much more complexity


Now get connect to shell of your device and use these commands ...

Now edit default.prop in the adb shell
> vi default.prop
and change ro.debuggable to 1

Next use these commands

