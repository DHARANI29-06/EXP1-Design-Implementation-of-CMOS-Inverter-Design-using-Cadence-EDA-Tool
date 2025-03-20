# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:
![Screenshot 2025-03-20 092416](https://github.com/user-attachments/assets/d04d5109-7a8f-4cdf-a3b7-53d809ef88e6)

#### 2. Transient Response Setup:
![Screenshot 2025-03-20 092536](https://github.com/user-attachments/assets/adfb6486-c21d-4da0-95e4-403b2b65bdb9)

#### 3. Voltage Transfer Characteristic (VTC)  Setup:
![Screenshot 2025-03-20 092631](https://github.com/user-attachments/assets/0fb0c4a4-8402-4269-a9b6-91d931b7aaa3)


## Output
#### 1.Transient Analysis Output
![WhatsApp Image 2025-03-20 at 09 41 13_8cc5a380](https://github.com/user-attachments/assets/61ba0610-ec28-4aec-86c0-07f122cfd191)

#### 2.DC Analysis Output
![Screenshot 2025-03-20 092557](https://github.com/user-attachments/assets/202a6db2-d427-441d-a697-fa4165b1d122)


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











