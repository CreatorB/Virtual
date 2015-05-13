Genymotion
----------

***Genymotion*** is not an emulator of Android but a virtualization based on virtual-box.This solution is the key of performance for android virtual device.Speed is an enormous advantage for developers, but when you are not programmer don't worry you can install it too, because it easy to install it.

### How to install

You can visit official site https://www.genymotion.com/#!/developers/user-guide

### Tips

* Ensure you have virtual-box installed firstly.
* If you encounted “INSTALL_FAILED_CPU_ABI_INCOMPATIBLE” error, install ARM Translation Installer v1.1 by dragging zip file onto virtual device HomeScreen.
* Install GApps as you need in the same way.
* Sometimes you may encount libGL.so file not found error.Resolving like find it by command if you are on linux “locate libGL.so | xargs ls -al”, and check whether the file exists or not.
* When you getting an error in first starting, you can try to restart your virtual box type command <code>sudo /etc/init.d/vboxdrv restart</code>
* When you have restarted your vbox but still not solve, you can re install dkms, google guide you. 

### Tricks

Alternatively, the above files can be packed together into a single archive file, typically with an .ova extension. Sure this ova have included with gapps and some apps, it's make simple way for you to work with genymotion.

Download ova : waiting uploading

+ Right click ova file and then open with oracle VM virtualbox (That's mean you must already installed virtualbox and genymotion)

![creatorb](https://raw.githubusercontent.com/CreatorB/Virtual/master/img/ss/genymotion-1.png)

+ Wait a moment, the ova file will import to your virtualbox and when it finished, it will be available on your list virtualbox manager

![creatorb](https://raw.githubusercontent.com/CreatorB/Virtual/master/img/ss/genymotion_2.png)

+ Now open your genymotion

![creatorb](https://raw.githubusercontent.com/CreatorB/Virtual/master/img/ss/genymotion_3.png)

+ and taraaa... You can see new virtual device on your genymotion

![creatorb](https://raw.githubusercontent.com/CreatorB/Virtual/master/img/ss/genymotion_5.png)

Let start and happy virtualing ,,,
