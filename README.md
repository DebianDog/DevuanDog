# DevuanDog
DevuanDog, based on the [Devuan](https://devuan.org/) 'Beowulf' branch, alpha version, under construction....   
[Forum thread](http://murga-linux.com/puppy/viewtopic.php?t=115124)  
**Update**: See [Here](https://debiandog.github.io/MakeLive/Readme-build-devuandog-beowulf.html) for a Devuandog build system.  


**Updated 2019-03-29**  
See here for [Changes and Fixes](http://murga-linux.com/puppy/viewtopic.php?p=1015137#1015137)  

### 32 and 64 bit ISO's    
  
Iso 32 bit: [DevuanDog-2019-03-29_32-bit.iso](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-2019-03-29_32-bit.iso) **Size: 290MB**          
Md5sum: [DevuanDog-2019-03-29_32-bit.md5](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-2019-03-29_32-bit.md5)      

Iso 64 bit: [DevuanDog-2019-03-29_64-bit.iso](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-2019-03-29_64-bit.iso) **Size: 315MB**              
Md5sum: [DevuanDog-2019-03-29_64-bit.md5](https://github.com/DebianDog/DevuanDog/releases/download/v1.0/DevuanDog-2019-03-29_64-bit.md5)      

DEVX and Firmware squashfs modules: [Here](https://github.com/DebianDog/DevuanDog/releases/tag/v1.1)         

Built from scratch by using debootstrap and remastered afterwards.     

Custom repository: [32-bit](https://fred181.gitlab.io/devuandog/i386/Packages/) [64-bit](https://fred181.gitlab.io/devuandog/amd64/Packages/)   

### Login details:
**root** with password **root**    
**puppy** with password **puppy**

**Specifications:**          
Kernel: 4.19.0-4 (change is that the kernel is separate module now)         
Choice of Boot Methods: porteus-boot and live-boot v3 (see for options [Here](https://github.com/DebianDog/DevuanDog/raw/master/Examples-boot-codes.txt))  
(EDIT: See post [Here](http://murga-linux.com/puppy/viewtopic.php?p=1015160#1015160) for how to boot with older kernel 3.16 if possibly your hardware is too old for booting v4.19)  
Default WM - OpenBox with on top PcmanFM (providing the desktop) and lxpanel.     
Option to switch to JWM window-manager                  
Default File Manager - PcmanFM with option to use rox.        
Default Internet Browser - Palemoon (replaced firefox-esr with palemoon).  

---      
 
**Screenshots:**  
    
Openbox with PcmanFM and lxpanel:  
![SCREENSHOT](https://github.com/DebianDog/DevuanDog/raw/master/DevuanDog-Openbox.png)      
JWM     
![SCREENSHOT](https://github.com/DebianDog/DevuanDog/raw/master/Devuandog-JWM.jpg) 

