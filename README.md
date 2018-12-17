# LM358synth
Pete McBennet's "simplest DIY"  dual oscillator synth at [https://www.youtube.com/watch?v=yZSkNASlMjM]. See also [https://www.youtube.com/watch?v=wPeH6KfH8RY] for layout on a breadboard. And [https://www.youtube.com/watch?v=GxnAC2Ivmbs]. There's another demo by Slider2732 at [https://www.youtube.com/watch?v=GxnAC2Ivmbs] which has another schematic that may be useful.

Schematic from [https://drive.google.com/file/d/0Bzxodk3UiKRgSXc0OVBWQnNfM00/view]

PCB also available at [https://www.pcbway.com/project/shareproject/Portable_LDR_Synthesizer_by_Jason_Cox.html]

![LDRsynth.JPG](./LDRsynth.JPG)

## BOM
#### Resistors:

- 47k:		R1 ,R6 ,R14 ,R31
- 22k:		R2 ,R7 ,R11 ,R28 ,R30 ,R33
- 10k:		R3 ,R24 ,R25 ,R32
- 100k:	R4 ,R5 ,R9 ,R10 ,R12 ,R26 ,R27
- 470k:  R8
- 4k7:   R15
- 390k:  R29

#### Pots, buttons etc:

- 50k pot: R13 - PWM balance
- 100k pot: R16-R23 - key tuning - *(Breadboarded with 1 'key' only!)*
- pushbutton, momentary: SW1-SW8 - *(Breadboarded with 1 'key' only!)*
- 2022382 jameco (10k): LDR1 & LDR2 - *For control of the filter by shading with hand/pot etc.*

#### ICs:

- LM358: U1-U5

#### Capacitors:


- 0u22F:  C1 					
- 0u001F: C4,C5  				

*Electrolytics:*

- 2u2F:  C2
- 4u7F:  C3
- 4u7F:  C6


## Notes on the circuit. 

I'm not sure where the little squares in the circuit diagram should be connected. Maybe they aren't connected at all... 

[https://e2e.ti.com/blogs_/archives/b/thesignal/archive/2012/11/27/the-unused-op-amp-what-to-do]

... Having implemented it, this is correct - or correct enough!

# Breadboard version

Here's the circuit implemented on a breadboard, with a single 'note' key:

![Breadboard](breadboard.jpg)

