Slit Spectrometer Project Log
====
The project is to build a slit spectrometer using a 300 lines/mm transmission grating and slit that I bought off of amazon for only $10 a piece. It will be based on the Sol'Ex spectrometer built by Christian Buil.
http://www.astrosurf.com/solex/sol-ex-presentation-en.html

**12-14-24**

Worked on understanding what the 3d print for the spectrometer will look like. I watched the YouTube video about putting together the Sol'Ex kit, and I downloaded the stl files. I do not know where to get step files ofr this or even if they're available. I might join one of the forums and ask about this.

One of the parts is printed with the very fine "telescope" threads. It's the "interface_tel_m42_#1.stl file.threads totally worked! I was surprised. Klipper does no allow '#' in a file name and I got an odd error from it, but I change # to num and it printed. NOTE: the kits sold by Azure3D use aluminum inserts instead of printed threads now.

The Sol'Ex has the ability to focus the collimator lens on the slit and also focus the camera lens. I think that I can use the same focus tube and lens mount that is used in that instrument for mine.

![](./pictures/3d_printed_parts.webp)

![](./pictures/assembled_solex.png)

12-21-24
Focusing the camera lens in the design of this spectrometer is more difficult that the Sol'Ex because the surplus lens I found for it is only 50mm focal length. It would be difficult to fit a helical focuser in this design look they do for the Sol'Ex. I'm designing a 3d printed focuser to do this. The idea is to use the tube-within-a-tube focuser design, but just use a screw to adjust the position - instead of a rack and pinion or other type of mechanism.
