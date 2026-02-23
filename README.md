# Inverting-Amplifier-using-Proteus
## Experiment 1
Design and Simulation of Inverting Amplifier using Op-Amp (μA741) in Proteus
## Aim
To design and simulate an Inverting Amplifier using μA741 Op-Amp in Proteus Design Suite and verify the voltage gain experimentally.
## Apparatus / Components Required
S.No	Component	Specification	Quantity
1	Op-Amp IC	μA741	1
2	Resistor R1	10 kΩ	1
3	Resistor Rf	100 kΩ	1
4	Signal Generator	Sine wave, 1 kHz	1
5	Dual DC Power Supply	+15V, -15V	1
6	CRO / Oscilloscope	Virtual (Proteus)	1
7	Connecting Wires	—	As required
## Theory
An Inverting Amplifier is a closed-loop amplifier configuration where the input signal is applied to the inverting terminal (-) of the op-amp through resistor R1, and feedback resistor Rf is connected between output and inverting terminal.
The non-inverting terminal (+) is grounded.
## Circuit Description
•	Pin 2 → Inverting input
•	Pin 3 → Non-inverting input (Grounded)
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → -15V
The input sine wave is applied through R1 and output is taken from pin 6.
## Circuit Diagram
![EX 1 ss](https://github.com/user-attachments/assets/bdc2ab94-a134-4638-be96-6f86818fae50)

## Tabulation
Input Voltage (Vin)	Theoretical Gain (Av)	Theoretical Vout	Practical Vout (Proteus)
<img width="958" height="459" alt="Screenshot 2026-02-23 085733" src="https://github.com/user-attachments/assets/b6ec7066-8998-4040-9b07-bf0d3807541a" />

## Simulation Procedure (Proteus)
1.	Open Proteus Design Suite
2.	Select components:
o	μA741
o	Resistors
o	AC Signal Generator
o	Oscilloscope
3.	Connect circuit as per inverting amplifier configuration.
4.	Set:
o	R1 = 10kΩ
o	Rf = 100kΩ
o	Input = 1V, 1kHz sine wave
5.	Apply ±15V power supply.
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
##  Waveform Observation
![EX 1 waveform](https://github.com/user-attachments/assets/79b1b074-45d5-458d-b2af-d1b7567767ec)

•	Input: Sine wave
•	Output: Amplified sine wave
•	Phase Shift: 180°
•	Gain ≈ -10
## Result
The Inverting Amplifier using μA741 Op-Amp was successfully designed and simulated in Proteus.
The practical output voltage closely matches the theoretical value.
The gain obtained is approximately -10, and the output waveform is inverted with respect to the input waveform.

