# 3340 VCO (VCO1)

~~**_I JUST REALISED THAT THIS VCO DESIGN STILL HAS SOME FLAWS. SOME RESISTOR VALUES NEEDS TO BE CHANGED AND ALSO I AM STILL NOT SATISFIED WITH THE SYNC FUNCTION. I WILL UPLOAD A REVISION OF THIS DESIGN ~LATE SUMMER~ END OF AUTUMN._**~~ 
**NEW GERBER FILES HAVE BEEN UPLOADED**

* Simple v/oct VCO based on the legendary CEM3340 (AS3340) ic
* Ac-coupled saw and pulse wave outputs
* Output signals deliver a peak-to-peak voltage of around 8V (Pulse might be a bit less)
* The effective frequency range goes from a bit under 15Hz up to 20kHz or more
* There is a coarse pot for setting the frequency in the just mentioned range and a fine pot for tuning within the range of few semitones
* Pulse width can be controlled with a pot (≈10-55%) or cv
* (Hard-)Sync with the possiblity to change the jumper (JP1) for 'positive' or 'negative' sync options 
* There are two trimmers - one to adjust the scale (to v/oct scale) and a high frequency trimmer for adjusting scale errors over 5kHz
* 4HP (quite slim but also a bit cramped!)
* Only through-hole parts
* Depth: ≈46mm

![VCO](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/VCO3340_1.jpg)
![VCO](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/VCO3340_2.jpg)
![Render](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/3340_VCO_PanelPcb.png)

## Schematics

![Schematics](https://github.com/diysynth/EURORACK-MODULES/blob/main/3340%20VCO%20(4HP)/3340_VCO_schematic.png)
