# LM358synth
Pete McBennet's "simplest DIY"  dual oscillator synth at [https://www.youtube.com/watch?v=yZSkNASlMjM]. See also [https://www.youtube.com/watch?v=wPeH6KfH8RY] for layout on a breadboard. And [https://www.youtube.com/watch?v=GxnAC2Ivmbs]. There's another demo by Slider2732 at [https://www.youtube.com/watch?v=GxnAC2Ivmbs] which has another schematic that may be useful.

Schematic from [https://drive.google.com/file/d/0Bzxodk3UiKRgSXc0OVBWQnNfM00/view]

PCB also available at [https://www.pcbway.com/project/shareproject/Portable_LDR_Synthesizer_by_Jason_Cox.html]

![LDRsynth.JPG](./LDRsynth.JPG)

## BOM
#### Resistors:

- 47k		1 ,6 ,14 ,31
- 22k		2 ,7 ,11 ,28 ,30 ,33
- 10k		3 ,24 ,25 ,32
- 100k	4 ,5 ,9 ,10 ,12 ,26 ,27
- 470k  8
- 4k7   15
- 390k  29

#### Pots, buttons etc:

- R13  					50k pot, PWM balance
- R16-R23 				100k pot - key tuning - try with 1 key only!


- LDR1 & LDR2 - 2022382 jameco (10k)

#### ICs:

- U1-5 LM358

#### Capacitors:

- C1 					0u22f
- C2 					2u2F +
- C3 					4u7F +
- C4,C5  				0u001F
- C6     				4u7F +


## Notes on the circuit. 

I'm not sure where the little squares in the circuit diagram should be connected. Maybe they aren't connected at all... 

[https://e2e.ti.com/blogs_/archives/b/thesignal/archive/2012/11/27/the-unused-op-amp-what-to-do]
