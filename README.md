# steelseries-gamedac-pulseaudio
Enable ChatMix and surround sound on the Steelseries Arctis Pro using PulseAudio profile files. Based off [the work by jannikw](https://github.com/jannikw/steelseries-arctis-pro-wireless)
## Installation
Copy 91-pulseaudio-steelseries-gamedac.rules to /etc/udev/rules.d 

Copy steelseries-gamedac-usb-audio.conf to /usr/share/pulseaudio/alsa-mixer/profile-sets 

Copy steelseries-gamedac-input.conf, steelseries-gamedac-output-chat.conf, steelseries-gamedac-output-game.conf to /usr/share/pulseaudio/alsa-mixer/paths/ 



**WARNING**: At the moment, you can't use the DAC's "Hi-Res" mode while these profiles are installed (this will be updated when I find a way). To restore original functionality, just delete the files you copied again and replug the DAC
