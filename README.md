# rollasplay
Low profile 34-key split keyboard with a roller encoder and finger splay.


Layout created using ergogen. Please note the schematic is therefore not actually related to the PCB file, but they should match...should...

If you see problems PLEASE let me know...I am still very new at this. (a few more details after the pics...)

![image](https://github.com/user-attachments/assets/89f0c3c5-4aca-4423-9dbb-c312a0478df8)
![image](https://github.com/user-attachments/assets/108ce0d8-c5d3-43a5-b4aa-93eef1cef227)
![image](https://github.com/user-attachments/assets/144cda5e-814c-4ca9-9dc1-a2831ee47c76)
![image](https://github.com/user-attachments/assets/a45214f6-f5c2-44e4-beb8-bbbb78bce867)

Once I validate and/or refine the design I hope to build it using direct-soldered Ambient Sunset silent tactile switches. I intend to SMD the diodes and controller on the front side of the board, then flip it and do the switches individually with a soldering iron.

If you're not familiar, this is the roller encoder in question: https://www.aliexpress.us/item/2251832804635444.html

They haven't been produced in a while so they're all new-old stock, and they keep getting pricier. But there's really nothing else around quite like them.

I got the XIAO Ergogen footprint from https://github.com/dohn-joh/emissary/tree/main/ergogen/footprints and removed the cutouts and through-holes for SMD.

Sadly the board is not reversable...the XIAO doesn't have symmetrical pins, and the surface mount doesn't allow for flipping it over. I will eventually make a right half. If you have ideas about better approaches to this problem please let me know.
