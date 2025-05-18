# How to use Your Android Phone as Router to Host a Minecraft Server if you don't have wifi card

------

**1**. First Open your World in Minecraft that you want to Host.

**2**. Press Esc -> Open to Lan.

**3**. Enter your preferred port (_In my case 25565_) -> Start

**4**. If you are on Windows,
* You need to install [adb](https://dl.google.com/android/repository/platform-tools-latest-windows.zip) or if you have scrcpy you can use its directory.
* Open the Folder where adb is installed in File Explorer
* In the address bar type cmd and press Enter.

 If you are on Linux,
* Open terminal and type 
```
sudo apt install adb
```


**5**. Connect for Android device📱via usb and as Usb Thethreing.

**6**. Enter the following commands

```
adb devices
```
(_To check whether your device is connected_)
     
 ```
 adb reverse tcp:<PORT> tcp:<PORT>
```
(_In my case 25565_)

**7**. Enable your Android Hotspot

**8**. Connect the Client pc with the ip address of phone and the port used above. (_I uses some apps like ftp server hoster to get ip of my phone.You can use anyone_).

Enjoy playing.

If you get any error, Feel Free to ask the [developer](mailto:yuyutshu08@gmail.com).
