Slit Spectrometer Project Log
====
The project is to build a slit spectrometer using a 300 lines/mm transmission grating and slit that I bought off of amazon for only $10 a piece. It will be based on the Sol'Ex spectrometer built by Christian Buil.
http://www.astrosurf.com/solex/sol-ex-presentation-en.html

**12-14-24**

Worked on understanding what the 3d print for the spectrometer will look like. I watched the YouTube video about putting together the Sol'Ex kit, and I downloaded the stl files. I do not know where to get step files ofr this or even if they're available. I might join one of the forums and ask about this.

One of the parts is printed with the very fine "telescope" threads. It's the "interface_tel_m42_#1.stl file.threads totally worked! I was surprised. Klipper does no allow '#' in a file name and I got an odd error from it, but I change # to num and it printed. NOTE: the kits sold by Azure3D use aluminum inserts instead of printed threads now.

The Sol'Ex has the ability to focus the collimator lens on the slit and also focus the camera lens. I think that I can use the same focus tube and lens mount that is used in that instrument for mine.

![](./pictures/solex_optics.png)

![](./pictures/3d_printed_parts.webp)

![](./pictures/assembled_solex.png)

12-21-24 

Focusing the camera lens in the design of this spectrometer is more difficult that the Sol'Ex because the surplus lens I found for it is only 50mm focal length. It would be difficult to fit a helical focuser in this design look they do for the Sol'Ex. I'm designing a 3d printed focuser to do this. The idea is to use the tube-within-a-tube focuser design, but just use a screw to adjust the position - instead of a rack and pinion or other type of mechanism.

12-26-24

I've been re-designing parts for the spectrometer in Fusion starting from the .stl files that you can download. Instead of making the spectrometer a box with a top and bottom, it will be a tube. The design has a "diving board" that connects the main spectrometer to the collimator block. The diving board wasbolted to the box in the .stl files. I've incoprated it into the main tube. I've redesigned the collimator block to make it easier to print iwhtout supports.

I tried printing the diving board, and I've made changes to it. Not sure if I'll print that part again, or just go for the whole thing. Printing the collimator block now.

I need to figure out how to hold the slit in place. 
Design the grating holder.
Design the focus tube and the camera lens holder. I've already taken a first pass at the focuser, but it doesn't have a way to hold the lens.
Count up the hardware necessary, and put some on order.

12-29-24

I've been working on the camera lens and focus mechanism. I have a design for that mechanism. I've printed the inner and outer tubes. The inner tube does not fit still.
I put the camera lens into the Fusion model, so I think I have a good position for the focus. I want to verify that this focus position is correct using the QHY camera.

On the slit side, I put the collimator lens into the model. The focus is far away from where I thought it would be. I looked at the Sol'Ex optics and the collimator lens has an 80 mm focal length. This explains why the focus in  model is 20 mm off.
I've put a screen shot of the optics in the pictures at the beginning of this log for reference
