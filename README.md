# Lenovo Ideapad 310-15IKB


Identifier:                  MacBookPro14,1
System Version:       Catalina 10.15.4 (19E266) > 10.15.4 (19E287) Supplemental Update
Kernel Version:         Darwin 19.4.0

Components:          
                                Intel Core i3 (7th Gen) 7100U / 2.4 GHz
                                Intel HD Graphics 620          
                                12 GB DDR4 SDRAM 2133 MHz

About:

You can pick your poison! There is an Opencore v0.5.7 or Clover revision: 5108. 
Both of these were tested with the install of 10.15 and upgraded via the Mac App store 
to 10.15.4 (19E266) with no modifications needed. 

Notes:

- Allthough Bluetooth works, the original NGFF WiFi is not compatible with macOS and must be replaced.
- Dont forget to edit the config.plist with the correct SMBIOS serials and etc.  

Included:
    - Opencore EFI
    - Clover EFI
    - Windows SSDTTime Outputs
    - Native ACPI Files

Opencore Notes:

        Working:
            - Sensors 
                Battery - Percentage, Voltage, Amperage 
                CPU -  Temp, Voltage, Useage
                GPU -  Temp, Voltage, Useage 
                HDD/SSD -  Temp, Life
            - Video (HDMI, VGA,and Camera)
            - Audio (Microphone, Speakers, Headphone, Bluetooth, and HDMI Audio)
            - Inputs (USB 3.0, DVD-RW, Trackpad, and Keyboard)
            - Network (Ethernet en0, WiFi en1, and Bluetooth)
            - Display (Brightness)      
            - iServices (Messages, Facetime, iCloud, App Store, TV, Music, Maps, and etc.)    

        Not Working:

            - Card Reader
            - Sleep (Only turns screen off)

        Needs Fixed:

            - FN (Function) keys
            - EDID
            - Functional Sleep
            - Automatic Brightness


Clover Notes:

        Working:
            - Sensors 
                Battery - Percentage, Voltage, Amperage 
                CPU -  Temp, Voltage, Useage
                GPU -  Temp, Voltage, Useage 
                HDD/SSD -  Temp, Life
            - Video (HDMI, VGA,and Camera)
            - Audio (Microphone, Speakers, Headphone, Bluetooth, and HDMI Audio)
            - Inputs (USB 3.0, DVD-RW, Trackpad, and Keyboard)
            - Network (Ethernet en0, WiFi en1, and Bluetooth)
            - Display (Brightness)
	    
        Not Working/Tested:

            - Card Reader
            - iServices (Messages, Facetime, iCloud, App Store, etc) have not been tested
            - Sleep (Only turns screen off)

       Needs Fixed:

            - FN (Function) keys
            - EDID
            - Functional Sleep
            - Automatic Brightness


