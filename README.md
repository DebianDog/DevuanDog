# DevuanDog
DevuanDog, based on the [Devuan](https://devuan.org/) 'Beowulf' branch, beta version.   
[Forum thread](http://murga-linux.com/puppy/viewtopic.php?t=115124)  
**Update**: See [Here](https://debiandog.github.io/MakeLive/Readme-build-devuandog-beowulf.html) for a Devuandog build system.  


**Updated 2019-07-11**     
See here for [Changes and Fixes](http://murga-linux.com/puppy/viewtopic.php?p=1015137#1015137)  

### 32 and 64 bit ISO's, two flavours:
- openbox with lxde components   
- openbox with xfce components      
(see specifications below)        

**Openbox with lxde:**    
Iso 32 bit: [DevuanDog-openbox_lxde-2019-07-11_32-bit.iso](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_lxde-2019-07-11_32-bit.iso) **Size: 309MB**          
[Md5sum](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_lxde-2019-07-11_32-bit.md5)      

Iso 64 bit: [DevuanDog-openbox_lxde-2019-07-11_64-bit.iso](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_lxde-2019-07-11_64-bit.iso) **Size: 339MB**              
[Md5sum](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_lxde-2019-07-11_64-bit.md5)   

**Openbox with xfce:**   
Iso 32 bit: [DevuanDog-openbox_xfce-2019-07-11_32-bit.iso](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_xfce-2019-07-11_32-bit.iso) **Size: 302MB**          
[Md5sum](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_xfce-2019-07-11_32-bit.md5)      

Iso 64 bit: [DevuanDog-openbox_xfce-2019-07-11_64-bit.iso](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_xfce-2019-07-11_64-bit.iso) **Size: 331MB**              
[Md5sum](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-openbox_xfce-2019-07-11_64-bit.md5)
      

DEVX and Firmware squashfs modules: [Here](https://github.com/DebianDog/DevuanDog/releases/tag/v1.1)         

Built from scratch by using debootstrap and remastered afterwards.     

Custom repository: [32-bit](https://fred181.gitlab.io/devuandog/i386/Packages/) [64-bit](https://fred181.gitlab.io/devuandog/amd64/Packages/)   

### Login details:
**root** with password **root**    
**puppy** with password **puppy**

**Specifications openbox with lxde:**          
Kernel: 4.19.0-5 (the kernel is separate module)         
Choice of Boot Methods: porteus-boot and live-boot v3 (see for options [Here](https://github.com/DebianDog/DevuanDog/raw/master/Examples-boot-codes.txt))  
(EDIT: See post [Here](http://murga-linux.com/puppy/viewtopic.php?p=1015160#1015160) for how to boot with older kernel 3.16 if possibly your hardware is too old for booting v4.19)  
Default WM - OpenBox with on top PcmanFM (providing the desktop) and lxpanel.     
Option to switch to JWM window-manager                  
Default File Manager - PcmanFM with option to use rox.        
Default Internet Browser - Palemoon (replaced firefox-esr with palemoon).

 **Specifications openbox with xfce:**          
Kernel: 4.19.0-5 (the kernel is separate module)         
Choice of Boot Methods: porteus-boot and live-boot v3 (see for options [Here](https://github.com/DebianDog/DevuanDog/raw/master/Examples-boot-codes.txt))  
(EDIT: See post [Here](http://murga-linux.com/puppy/viewtopic.php?p=1015160#1015160) for how to boot with older kernel 3.16 if possibly your hardware is too old for booting v4.19)  
Default WM - OpenBox with on top xfdesktop (providing the desktop) and xfce4-panel.     
Option to switch to JWM window-manager                  
Default File Manager - Thunar with option to use rox.        
Default Internet Browser - Firefox-ESR.   

---      
 
**Screenshots:**  
    
Openbox with PcmanFM and lxpanel:  
![SCREENSHOT](https://github.com/DebianDog/DevuanDog/raw/master/DevuanDog-Openbox.png)      
JWM     
![SCREENSHOT](https://github.com/DebianDog/DevuanDog/raw/master/Devuandog-JWM.jpg) 
