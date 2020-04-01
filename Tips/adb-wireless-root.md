# Access your android device through adb in wireless way ? NO usb connection needed ?


Always feel lazy to connect to my android to computer and then opening tcp port to make a wireless connection. But this method what Im telling you now dont require you to connect android to your pc even one time also…. to access it in wireless way?

Things require to make it possible

- A rooted mobile
- Both your phone and pc must be connected to same wife network
- [adb tcpip root apk](https://play.google.com/store/apps/details?id=pl.witampanstwa_.adbtcpip&hl=en_IN) (root required)

open the app and hit toggle

Next open your terminal in your pc and connect to the ip given over there with ```adb connect <ip>:5555```
