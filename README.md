**Simple Buzzer Alarm PCB**

**📌 Project Overview****

This project demonstrates the design of a simple buzzer alarm circuit using the NE555 Timer.

The PCB was designed using KiCad.

The 555 timer is configured in astable mode to generate a square wave signal that drives a Piezo Buzzer, producing a continuous alarm sound when power is applied.

**⚙️ Features**

 Simple buzzer alarm circuit
 
 555 timer based oscillator
 
 Custom PCB designed in KiCad
 
 Beginner-friendly electronics project
 
 Suitable for learning PCB design and IC circuits
 
**🧩 Components Used**
 NE555 Timer

 Piezo Buzzer
 
 Resistor (R1 – 1kΩ)
 
 Resistor (R2 – 10kΩ)
 
 Capacitor (10µF)
 
 Capacitor (0.1µF)
 
 2-pin power input connector
 
**🔌 Working Principle**

The 555 timer IC operates in astable mode to generate periodic pulses.
When power is supplied, the capacitor begins charging through the resistors.
Once the voltage reaches the threshold, the capacitor discharges.
This charging and discharging cycle creates a square wave output at pin 3 of the 555 timer.
The output signal drives the buzzer, producing a continuous alarm sound.

**🖥️ Software Used**
 KiCad – schematic design and PCB layout
 
** 📂 Project Structure**
**Simple-Buzzer-Alarm-PCB**
│
├── Schematic
├── PCB_Layout
├── Gerber_Files
└── README.md

**🚀 Applications**
 Alarm systems
 Electronic learning projects
Sound indicators
Embedded system experiments
