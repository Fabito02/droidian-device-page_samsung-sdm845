## Features & Usability

|                               	|    	|                                  	|    	|                      	|   	|
|-------------------------------	|----	|----------------------------------	|----	|----------------------	|---	|
| Manual brightnes              	|  ✅ 	| Battery lifetime > 24h from 100% 	|  ✅ 	| Automatic brightness  |  ✅  	|
| No reboot needed for 1 week      	|  ✅	| Fingerprint reader  	                |  ✅✅   | Waydroid		|  ✅	|
| Torchlight                    	|  ✅	| Boot into UI                     	|  ✅ 	| GPS                 	| ❔  |
| Vibration                     	|  ✅ 	| Hardware video playback          	|  ✅ 	| Proximity          	|  ✅ 	|
| Flashlight                    	|  ✅	| Anbox patches                    	|  ✅ 	| Rotation            	|  ✅ 	|
| Photo                         	|  ✅	| AppArmor patches                 	|  ✅ 	| Touchscreen          	|  ✅ 	|
| Video                         	|  ✅	| Battery percentage               	|  ✅ 	| Earphones           	|  ✅	|
| Switching between cameras     	|  ✅	| Offline charging                 	|  ❔	| Loudspeaker          	|  ✅	|
| Dual SIM functionality        	| ✖️ ✖️  	| Online charging                  	|  ✅ 	| Microphone          	|  ✅	|
| Carrier info, signal strength 	|  ✅ 	| SD card detection and access     	|  ✅ 	| Volume control       	|  ✅ 	|
| Data connection               	|  ✅ 	| RTC time                         	|  ✅ 	| Pin unlock           	|  ✅ 	|
| Incoming, outgoing calls      	|  ✅ 	| Shutdown / Reboot                	|  ✅ 	| ADB access          	|  ✖️✖️  	|
| MMS in, out                   	|  ❔ 	| Wireless External monitor        	|  ✖️✖️	| MTP access           	|  ✅✖️  	|
| SMS in, out                    	|  ✅ 	| Bluetooth                        	|  ✅ 	| WiFi			|  ✅	|
| Change audio routings          	|  ✅	| Flight mode                      	|  ✅ 	| Hotspot		|  ✅	|
| Voice in calls                	|  ✅ 	|

- **✅** *Confirmed working.*
- **✅✖️** *Working to some extent but with issues.*
- **✖️** *Not Working.*
- **❔** *Not tested.*
- **✖️✖️** *Global issue.*

## Requirements
- Stock Android 10

## Files
- Download the latest fastbootable image: [droidian-UNOFFICIAL-phosh-phone-samsung_yourdevice-api29-arm64-nightly_20260515.zip](https://github.com/Fabito02/droidian-images/releases).

## Installation
* Extract the archive
* Flash the recovery for your device: [S9/S9+](https://xdaforums.com/t/recovery-unofficial-twrp-for-galaxy-s9-s9-snapdragon.4369025/) or [Note 9](https://xdaforums.com/t/recovery-unofficial-twrp-for-galaxy-note-9-snapdragon.4369023/)
* Boot to TWRP and in the reboot section boot to fastboot
* run the flash_all script

## UBports Installer
- Alternatively the UBports installer can also be used to install Droidian.

## Notes
- The default password is `1234`.

## Bugs
- Encryption works but will make the device very slow so it is recommended to not be enabled for now.
- Mobile data needs an APN to be set up from Settings -> Mobile -> Acess Point Names.
- Mobile data might stop working after making or recieving phone calls. Toggle Mobile Data from the settins off/on.
- Dual SIM functionality is currently not implemented in Phosh so only one SIM works at the moment.

## Final notes
- I'm not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.
- Please do some research if you have any concerns about features included in the products you find here before flashing it!
- YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.

# Support
- Droidian telegram group: [@DroidianLinux](https://t.me/DroidianLinux).
