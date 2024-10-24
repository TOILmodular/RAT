# RAT - A dual Eurorack distortion module
This module is a Eurorack version of the RAT guitar distortion pedal.
It contains two separate circuits, using the OP07N op amp.
The two inputs are normalled to each other.
Instead of a volume knob and a bypass switch given on the effect pedal, the module has a wet/dry mix knob for each channel.

<img height="500" src="https://github.com/user-attachments/assets/60a1b3fe-ca7f-472f-991a-b350e9224391">
<img height="500" src="https://github.com/user-attachments/assets/5f3d53a6-8f36-49fe-ba2f-99965a934508">

<img height="500" src="https://github.com/user-attachments/assets/d4e88953-52b5-4f61-88f0-1f2658739ed0">
<img height="500" src="https://github.com/user-attachments/assets/0fafc53f-b85f-41b9-8022-13580fb2b1ae">

A demo of the module is available on YouTube.

[<img width="500" src="https://github.com/user-attachments/assets/80b52a6f-7850-4199-8312-8c6b3417a3ea">

## Module Build and PCBs
I added two different versions for the control board in the folder GerberFiles, an "original", and a "Thonk" version.
Reason is that for my own module, I am using specific potentiometers - 16K4 series from Supertech Electronics - and 3.5mm jack sockets - MJ-355 from Marushin - available at my local electronics shop.

<img width="200" alt="CtrlPCB Orig" src="https://github.com/user-attachments/assets/b288da83-0ec3-4b87-95a7-00d5ec1ac544">

However, since most DIY projects for Eurorack modules out there are using potentiometers from ALPHA and so-called THONKICONN jacks, as they are provided by Thonk in the UK, I also created another control board PCB for the "Thonk" version with footprints for those components.

<img width="200" alt="CtrlPCB Thonk" src="https://github.com/user-attachments/assets/4a26d78b-67c7-48a9-96c5-5ca7b66637bc">

The main PCB is the same for both versions.

<img width="200" alt="MainPCB" src="https://github.com/user-attachments/assets/2b259b6d-f2c7-40ba-a6cd-c890b6a672f2">

I created the Gerber files with the online tool EasyEDA and ordered the PCBs at JLCPCB.

## Components
The module is mainly built out of THT components. The only exception are the 0.1 uF bypass caps for all the op amps, which are 1608 (0603) SMD components.

The original Pro Co guitar pedal circuit from 1978 makes use of the LM308 op amp in the central distortion segment. Later redesigns introduced the OP07 op amp instead, which I am also using in my module.
