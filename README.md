# computer-brain
Computer Brain
The Computer Brain is a LED matrix is designed to give off a retro computer vibe. The use of the 6502 CPU and the random arrangement of the LEDs are a nod to the early days of computing, when computers were much simpler and more limited. The LED matrix can be used to display a variety of patterns, which can be used to create a visual representation of the CPU's activity or to simply add a bit of retro flair to your workspace.

The MOS 6502 controls the LED matrix by outputting certain patterns on the address line. For example, inputting the hex value AE will have the CPU count in binary from 0 to 255. The LED matrix is designed to be used for aesthetic purposes, such as creating a visual representation of the CPU's activity.

Requirements
Qty  Name 
1	  6x6 Switch 
1	  USBMicroPower
1	  2.2u Electrolytic capacitor 
1	  DIP switchEI-08  
1	  104 potentiometer 
1	  NE555N 
1	  MOS 6502 
1	  8 pin socket
1	  40 pin socket	
1	  6cm standoff
2	  10k resistor	
2	  .1nF ceramic capacitor	
9	  1K resistor	 
15	51R resistor	
48	LED-Red



Instructions
Solder all components as per the Instructions page.

Usage
The LED matrix can be used to display a variety of patterns. To display a pattern, you need to input the hex value of the pattern into the address line of the MOS 6502 CPU through the DIP switched. For example, the hex value AE would display the pattern that counts from 0 to 255, but due to the random positioning of the LEDs you get that old server room computer feeling.

Limitations
The LED matrix is limited by the number of patterns that can be displayed. The current design can display 256 different patterns.

Credits
This project was created by The Hackers Workshop.

License
This project is licensed under the CERN Open Hardware License (CERN OHL).
