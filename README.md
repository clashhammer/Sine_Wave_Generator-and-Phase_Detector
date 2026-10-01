# Sine-Wave-Generator-and-Phase-Meter
Two projects I made and want to showcase

<h1>1. Sine Wave Generator</h1>  
<h3>Description:</h3>
A compact electronic signal generator based on a Wien-bridge oscillator. A UA741 operational amplifier provides the amplification, while an RC feedback network determines the oscillation frequency. The circuit produces a continuous, relatively clean sinusoidal output that can be viewed and measured with an oscilloscope. The completed circuit produces a signal of roughly 1.2 kHz.

## Main parts

| Quantity | Part |
|---:|---|
| 1x | UA741 Operational Amplifier IC |
| 1x | 10kΩ Dual-Gang Potentiometer |
| 2x | 10 nF Capacitors |
| 1x | 20kΩ Resistor |
| 1x | 4.7kΩ Resistor |
| 2x | 1N4007 Diodes |
| 1x | 10kΩ Resistor |
| 2x | 9V Batteries |
| 1x | Breadboard |
| Several | Jumper Wires |

Schematic:
<img width="1600" height="1184" alt="image" src="https://github.com/user-attachments/assets/659041c9-0a6b-4db7-991f-40008ccd38aa" />

Breadboard build:
<img width="972" height="877" alt="Untitled Design (5)" src="https://github.com/user-attachments/assets/af688907-b03c-4eb6-a57c-00076d991ce3" />

<h1>2. Non-Contact Phase Detector</h1>  
<h3>Description:</h3>
The phase meter is a non-contact AC voltage detector designed to detect live wires without making electrical contact with the conductor. A sensing wire picks up the alternating electric field around an AC wire through capacitive coupling. Because this signal is extremely weak, an LM358 operational amplifier amplifies it to a usable level. The amplified signal then activates the output indicator (an LED and a buzzer), showing when a live conductor is nearby. The circuit can be used for locating live wires and checking for the presence of AC voltage from a short distance.

## Main parts

| Quantity | Part |
|---:|---|
| 1x | LM358 Operational Amplifier IC |
| 1x | 2N2222 NPN Transistor |
| 1x | 10kΩ Potentiometer |
| 1x | 1 MΩ Resistor |
| 1x | 100 kΩ Resistor |
| 1x | 2.2 kΩ Resistor |
| 1x | 1 kΩ Resistor |
| 2x | 100 nF Capacitors |
| 1x | LED |
| 1x | Active Buzzer |
| 1x | Sensing Antenna (insulated copper wire) |
| 1x | 9V Battery + battery clip wire|
| 1x | Piece of perfboard|
| Several | Connection wires | 

Schematic:
<img width="1600" height="1301" alt="image" src="https://github.com/user-attachments/assets/66c1e92f-9cb9-4314-9aa4-5a2a18b24449" />

Perfboard build:
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/a5abb26f-7ab0-4a5b-a88d-f4b2d20c31a2" />

