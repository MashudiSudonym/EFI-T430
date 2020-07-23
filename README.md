# EFI for Thinkpad T430
## Check my youtube video for tutorial :
Part 1 : 

## My Laptop Spesification :
* Thinkpad T430
* Processor : Intel(R) Core(TM) i5-3320M CPU @ 2.60GHz (4 CPUs), ~2.6GHz
* Display : Intel(R) HD Graphics 4000 (1366 x 768)
* Wireless Intel(R) Centrino(R) Advanced-N 6205

### What's work
* Intel Hyperthread (4/8 cores) - I have the i5-3320M.
* Intel TurboBoost
* Intel SpeedStep
* CPU HW Monitor (temps, clock and power)
* RAM DDR3 at 1600mhz
* Intel HD4000 1536MB
* Brightness (FULL Range + Fn Brightness Keys)
* Battery Status
* Display turns on automatically on wake/instant wake
* USB 3.0 Full Speed
* Audio ALC269
* Webcam
* Keyboard + TouchPad + TrackPad
* Bluetooth

### Maybe work 
* Display Port Out: FullHD + Audio (untested i don't have external * monitor)
* Ethernet (untested i don't have LAN Network Connection)
* Sleep (i think this is work but not perfectly)
* Mic
* SD Card Reader (untested i don't have SD Card)

### Not Working
* VGA output
* Wireless Intel(R) Centrino(R) Advanced-N 6205
* Biometric Device Fingerprint Reader

### Tools Sources :
* source vanilla image Catalina 10.15.6 : [link](https://www.olarila.com/topic/6278-new-vanilla-olarila-images/)
* source Win32DiskImager : [link](https://sourceforge.net/projects/win32diskimager/)
* source Thinkpad T430 tutorial for create DSDT and other basic configuration if you can not using my custom EFI folder Configuration or you have a different spesification of Thinkpad T430 : [link](https://github.com/drasbeck/macos-thinkpad-t430/blob/master/README.md)
* source Clover installer r5070 : [link](https://sourceforge.net/projects/cloverefiboot/files/Installer/Clover_v2.5k_r5070.zip/download)
* source my own EFI (include DSDT and other, easy way if you have same spesification like my laptop) : [link](https://s.id/efiT430)
* source Exploler++ : [link](https://s.id/winEPlusPlus)
* source MiniToolPartitionWizard : [link](https://www.partitionwizard.com/free-partition-manager.html)


#### Special Credit for
[https://github.com/drasbeck/macos-thinkpad-t430/blob/master/README.md](https://github.com/drasbeck/macos-thinkpad-t430/blob/master/README.md)