# Hackintosh-p558

EFI boot folder based on OpenCore for Fujitsu P558/E85+  
Last update: May 17th 2024  

/!\ WARNING = Project in standby. No futur update planned.

## Description

EFI files based on OpenCore  
OpenCore version: 0.9.8  
MacOS version: __Sonoma 14.3__

## Hardware

**Desktop Fujitsu Esprimo P558**  
![Fujitsu P558  ](/Assets/FujitsuP558.png "Fujitsu P558")  
[Datasheet P558](/Assets/Fujitsu-ESPRIMO-P558-E85-Datasheet.pdf)  
[Datasheet D3600 Motherboard](/Assets/Fujitsu-Mainboard-D3600-D3601.pdf)  

| Type	| Name                   |
|:------|:-----------------------|
| CPU	| Intel i3 8100 |
| RAM	| 2xDDR4 2444MHz - 8Gb |
| GPU	| Intel UHD630 |
| Drive	| SATA SSD 1000 Gb |
| Sound card	| Realtek ALC671 |
| WLAN	| No WLAN |
| LAN	| Realtek RTL8111G |
| Display	| DVI or HDMI (no VGA support) |

## SMBIOS Info

System Product Name : iMac 20.1  
System Serial : <Serial_Number>  

## Working and Not-Working

### Working

### Not-Working
Never boot at the moment due to ACPI error. Fixed on march !  
But no iGPU support with UHD630. Need framebuffer BusID patch.    

## Screenshots
Need update. 

## Credit
Based on my previous P420 https://github.com/arduinovc/hackintosh-p420  
