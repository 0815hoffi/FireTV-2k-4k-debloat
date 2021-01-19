For Fire TV Lite without root go to https://github.com/0815hoffi/FireTV-2k-4k-debloat/tree/main/FireTVLite


!!! All Data will be Lost !!!
!!! No Access to Search and Amazon Store !!!
!!! Amazon Launcher will be replaced with Wolf Launcher !!!


1, Download All.

2, Download Firmware 

   2k = https://www.mediafire.com/file/b7dw9i9kqzjmn29/ftvs2k-5.2.7.7.zip/file
   
   4k = 
   
   and Copy ftvs2k-5.2.7.6.zip and ftvs4k_6.2.7.6.zip to Root Folder.

3, Enable ADB Debugging in FireTV Setting.

4, Test if ADB working  ( command line > #adb shell )

5, Reboot to TWRP with connected USB Cable
   
   adb shell reboot recovery
   
   ( Not use an OTG-Cable )

6, run 1-Firmware.cmd and Select your device 
   !!! All Data will be lost !!!
   
7, Wait for Device comming Up.
   
   Complete Amazon OOBE.
    
   Enable ADB Debugging in FireTV Setting.
    
   Test if ADB working  ( command line > #adb shell )
    
   Test and Allow Root for adb shell 
   command line > #adb shell 
   command line > #adb shell su
    
   If you have Root Access on adb shell go to next Step
    
 
8, run 2-Settings.cmd
    
   Debloat Script will run and Reboot 2 time, wait
   for device to come Up.
   
9, run 3-CleanSDcard.cmd to Clean the FireTV Storage if you want.

10, Done
     
