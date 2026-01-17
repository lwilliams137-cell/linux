# linux
Config files for workstation utility

I included a parametric equalizer for adjustable tone.
I increased the 3.4 kHz gain for clearer vocals.
You can download a customized EQ per your iem/headphones from https://autoeq.app.
It is also a good idea to add a Limiter to combat treble hissing.

Next, I included left & right True Stereo convolver files.
It creates a 3D soundstage for iem.
You can download the entire m7 collection from https://samplicity.com/bricasti-m7-impulse-response-files.
As all effects, lower the input gain to -3.0 dB to protect your electronics from power spikes.

Then, I forced Pipewire to use higher audio bitrates.
Copy the ClockRates files to "~/home/X/.config/pipewire/pipewire.conf.d/".
X is your username.
Run "systemctl --user restart pipewire pipewire-pulse wireplumber" to reload Pipewire services.


Also, I included a customized mpv configuration file.
I enabled sharpness and GPU processing for enhanced video playback.

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
  

