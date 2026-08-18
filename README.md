# LiPo Battery Charger - My First PCB Design

Hi! Welcome to my hardware project. 

This is my very first attempt at designing a Printed Circuit Board (PCB). I made this project mainly to learn how to use **Altium Designer**. Instead of just drawing a circuit on paper, I wanted to learn how to actually place components, add 3D models, and do basic routing on a physical board.

### What This Board Does
It is a simple charger for Lithium-Polymer (LiPo) batteries. I added a few helpful features to it:
* **Two Power Options:** You can power the board using a Micro-USB cable or a standard DC barrel jack. 
* **Adjustable Charging:** I added a small solder jumper on the board. This lets you choose between a 100mA or 500mA charging speed depending on the battery size.
* **Safety Markings:** I added clear text (silkscreen) on the board to show exactly where the battery goes and what the max voltage is, so nothing gets plugged in backward.

### Folder Layout
I organized my files to keep things clean:
* `/Docs` - Contains 3D pictures of the finished board and a PDF of the circuit schematic.
* `/Hardware` - Contains my raw Altium Designer files (`.SchDoc` and `.PcbDoc`).

### My Experience
Since this was my very first time using Altium, I focused mostly on understanding the software interface and getting the parts placed correctly without any errors. The routing was done a bit quickly just to get the hang of connecting things, so I know the power tracks could be thicker. Overall, I learned a lot about how PCB software works, and I'm excited to take more time and do advanced routing on my next project!
