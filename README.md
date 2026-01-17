# linux
Config files for workstation utility

I included a parametric equalizer for adjustable tone.
I increased the 3.4 kHz gain for clearer vocals.
You can download a customized EQ per your iem/headphones from https://autoeq.app.
Parametric equalizers are more complex than graphic equalizers since you can make additional adjustments beyond volume. A parametric equalizer lets you control three aspects: level (boosting or cutting decibels), the exact frequency, and the bandwidth or range (also known as Q or quotient of change) of each frequency. As such, parametric equalizers offer surgical precision when it comes to affecting the overall sound. It is also a good idea to add a Limiter to combat treble hissing.

Next, I included left & right True Stereo convolver files.
It creates a 3D soundstage for iem.
You can download the entire m7 collection from https://samplicity.com/bricasti-m7-impulse-response-files.
Convolver files, or impulse response (IR) files, are used to simulate the acoustics of real spaces or effects by blending audio signals with recorded echoes from those environments. They allow for creative sound manipulation, such as adding reverb or unique filtering effects to audio tracks.
As with all effects, lower the input gain to at least -3.0 dB to protect your electronics from power spikes.

Then, I forced Pipewire to use higher audio bitrates.
While Pipewire internally supports up to 64-bit 768 kHz audio depth, it sometimes downscales to 16 bit 44 kHz. 
Copy the ClockRates files to "~/home/X/.config/pipewire/pipewire.conf.d/".
X is your username.
Run "systemctl --user restart pipewire pipewire-pulse wireplumber" to reload Pipewire services.

Also, I included a customized mpv configuration file.
I enabled sharpness and Nvidia GPU hardware acceleration for enhanced 4K video playback.

Finally, my top 10 free apps:
  * Btop https://github.com/aristocratos/btop
  * Celluloid https://celluloid-player.github.io
  * LibreOffice https://www.libreoffice.org
  * LMStudio https://lmstudio.ai
  * OBS https://obsproject.com/
  * Qalculate https://qalculate.github.io
  * Shortwave https://github.com/maunalinux/shortwave
  * Strawberry https://www.strawberrymusicplayer.org
  * Wikit https://github.com/KorySchneider/wikit
  * VScodium https://github.com/VSCodium/vscodium
  

