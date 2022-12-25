# 3340 VCO (VCO1)
* Simple v/oct VCO based on the legendary CEM3340 (AS3340) ic
* Ac-coupled saw and pulse wave outputs
* Output signals deliver a peak-to-peak voltage of around 8V (Pulse might be a bit less)
* The effective frequency range goes from a bit under 15Hz up to 20kHz or more
* There is a coarse pot for setting the frequency in the just mentioned range and a fine pot for tuning within the range of few semitones
* Pulse width can be controlled with a pot (≈10-55%) or cv
* (Hard-)Sync input 'resets' the triangle core - works best (or only) with pulse or square waves from a master vco (sawtooth waves might work too)
* There are two trimmers - one to adjust the scale (to v/oct scale) and a high frequency trimmer for adjusting scale errors over 5kHz
* 4HP (quite slim but also a bit cramped!)
* Only through-hole parts
* Depth: ≈46mm

This VCO is not perfect but works quite well and has good pitch-tracking capabilities. The sync and PWM inputs can be a bit 'quirky' depending on the input signals -
but considering this VCOs relatively low part-count it works fine.

![VCO](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/VCO3340_1.jpg)
![VCO](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/VCO3340_2.jpg)
![Render](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/3340_VCO_PanelPcb.png)

## Schematics

![Schematics](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/3340_VCO_schematic.png)
