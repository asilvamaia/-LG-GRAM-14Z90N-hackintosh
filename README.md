# LG GRAM 14Z90N
Hackintosh completo deste laptop. 
Opencore Version: 0.94

OS 	VENTURA
Model 	LG gram 14 - 2020 (14Z90N-V-P2)
Processor 	Intel Core i5-1035G7
Integrated Graphics 	Intel® Iris® Plus
Memory 	16GB RAM & 480gb SSD

Instructions

1. BIOS Settings

    Hold F2 to enter BIOS on boot up
   
    Press CTRL-ALT-F7 to open Advanced Options
   
    Main - Boot Features - Quick Boot => Disabled
   
    Advanced - Intel Advanced Menu - CPU Configuration - Software Guard Extentsions (SGX) => Disabled
   
    Advanced - Intel Advanced Menu - Power & Performance - "CPU - Power Management Control" - CPU Lock Configuration - CFG Lock => Disabled and Overclocking Lock => Disabled
   
    Advanced - Intel Advanced Menu - System Agent (SA) Configuration - Graphics Configuration - DVMT Pre-Allocated => 64M
   
    Advanced - Intel Advanced Menu - Platform Settings - System Time and Alarm Source => Legacy RTC
   
    Exit - Exit Saving Changes

Working

    WIFI
    Sound
    Graphics Acceleration
    Keyboard
    Webcam
    FN keys for audio volume
    Trackpad
    Bluetooth
    Ethernet (USB-C Adapter)
    Battery Status
    FN Keys

Not tested
    
    Thunderbolt / USB C

Not Working

    HDMI - Not work for Comet Lake processors
    FingerPrint Reader

Need change the original SSD, because original is incompatible with Hackintosh. Use a NVME Western Digital. 
    
