# stop using adb to connect to frida

Start ssh service in your mobile android through sshdroid apk 

Full guide here  [ssh in android](https://github.com/balook/android/blob/master/Tips/ssh_in_android.md)

Now tunnel the ssh to localhost in pc => Remeber both pc and phone must be connect to same __wifi__ connection

```
ssh -L 27042:127.0.0.1:27042 <hostname> -l <username> -p <port>
```
Suppose if ssh connect part is root@192.168.0.100:2222

```
ssh -L 27042:127.0.0.1:27042 192.168.0.100 -l root -p 2222
```

To connect to frida use 

frida-ps -R

**-R for remote**

**-U for usb**
