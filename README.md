# Analog-Electronics-semiconductors-final-project
This was the final design of my Analog Electronics (semiconductors) class. The project required the design of a circuit that used a transducer in a bridge circuit to along with an instrumentation amplifier and ZENER diode to produce an output voltage varying from -5V to 5V when the transducer was turned.

My partner and I were tasked with providing a system of equations to mathematically select the resistors used in the circuit based on the input voltage. The input voltage was regulated based on the ZENER diode chosen. 

We desingned and tested the circuit virtually with the help of Pspice before ordering all of the necessary parts and testing the physical circuit in a breadboard. We used a variable resistor (potentiometer) as the transducer. One of the largest problems was that the resistors in the bridge circuit had to be balanced by adding very small resistances. The slight tolerances of the resistors that we bought were enough to through the output off drastically. After hours of trouble shooting we were ready to solder the parts into a proto board.

The circuit preformed very well relative to our classmates. Spinning the potentiometer all the way to one side resulted in a 5V output while spinning the potentiometer all the way in the other direction resulted in a -5V output. The ZENER diode preformed very well at regulating the input voltage of the circuit as well. Many other teams had to replace their diodes either because of factory defects or because they burned them out during the soldering phase.

My final report is attatched with pictures of the circuit, the voltage outputs, the Pspice simulation, and the Altium Circuitmaker pcb board that I designed that could be used with this circuit

