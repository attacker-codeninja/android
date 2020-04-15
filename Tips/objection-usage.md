# Objection commands i used VERY helpful ... ! (Android)

Befor using objection you have to start frida server in your android
Normally people use ./frida & command but its being lazy to use every time this comamdn
 instead install magisk module in your phone .
 Frida will run everytime .
 you can wheck whether frida is running or not like 
 useing 
 ```
 ps -e | grep frida (or) ps | grep frida
 ```

- frida server  starts running

- objectiion -g com.package explore

- [screenshots](https://github.com/sensepost/objection/wiki/Screenshots)

```
ls
env
cd <path-in-env>
file download <some>.<extension>

android intent launch_activity com.airbnb.android.activities.MainActivity
jobs list
pwd print
```

```
android hooking list classes
android hooking list class_methods
andorid hooking list activities
android shell_exec <command ex: ls>
```

android root simulate => root-detection-enable
android root disable => root-detection-disable


android keystore list
android keystore watch


file http  start
file http status
file http stop


## using sql browser 
```
cd /data/user/0/com.google.android.youtube
sqlite connect <databases-any>  
.tables
```

```
frida => For checking frida version

```

Resources 
https://android.jlelse.eu/hacking-android-app-with-frida-a85516f4f8b7
https://github.com/sensepost/objection/wiki/Using-objection
