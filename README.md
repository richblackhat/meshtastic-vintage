# meshtastic-vintage
Welcome to Meshtastic Village
Install Meshtastic on a Heltec V2 or any other outdated device
by using this guide and Repo.

I am RichBlackhat, and one day I noticed my Lora TTGO V1 and my Heltec V2.1 were no longer supported by meshtastic!
and i got upset because it is still a good hardware! and at least the Heltec v2 is extremely well priced, and really easy to find.
so it is a great device to get started on this underworld we know as "the mesh" 

I want to make this easy for you so, if you  want the solution to install meshtastic firmware on your heltec v2 and make it work perfectly is:

Download your firmware from this repo, this firmware was compiled by me and many other users.
the latest addition is the firmware-heltec-v2_1_2.7.9 beta_firmware contributed by the user yo8aiv, who by the way created also hardware mods for the heltec v2, check his profile: github.com/yo8aiv 

once you downloaded the firmware of your selection just use the web ESP tool to flash the firmware instead of the official meshtastic flasher


*note. before you flash the firmware. remember the basic requirements is to have the correct driver installed. (windows: Silicon Labs cp210x Usb to Uart Bridge) 

use the ESPwebtool just visit: https://esptool.spacehuhn.com/
plug your device and press connect
select your device
delete any other "partition" you might already have on the device by pressing the trash icon 
create a new one and select your firmware file, and press flash

wait until it finishes and you now have installed meshtastic on your heltec V2

my youtube channel is:
https://youtube.com/richblackhat
