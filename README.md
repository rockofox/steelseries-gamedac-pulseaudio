**NOTE: I no longer actively use this headset. But if something breaks, contact me and I'll try to help you fix it.**

# steelseries-gamedac-pulseaudio
Enable ChatMix and surround sound on the Steelseries Arctis Pro using PulseAudio profile files. Based off [the work by Witek094](https://github.com/Witek094/steelseries-arctis-pro-wireless-pulseaudio-profile)
## Installation
Copy 91-pulseaudio-steelseries-gamedac.rules to /etc/udev/rules.d 

Copy steelseries-gamedac-usb-audio.conf to /usr/share/pulseaudio/alsa-mixer/profile-sets 

Copy steelseries-gamedac-input.conf, steelseries-gamedac-output-chat.conf, steelseries-gamedac-output-game.conf to /usr/share/pulseaudio/alsa-mixer/paths/ 



**WARNING**: At the moment, you can't use the DAC's "Hi-Res" mode while these profiles are installed (this will be updated when I find a way). To restore original functionality, just delete the files you copied again and replug the DAC
