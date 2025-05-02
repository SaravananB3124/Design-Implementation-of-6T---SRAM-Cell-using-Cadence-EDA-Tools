## Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![IMG-20250503-WA0022](https://github.com/user-attachments/assets/7bca7c86-c464-467a-b229-a4bef4b05bc5)



## 6T SRAM Truth Table

![IMG-20250503-WA0021](https://github.com/user-attachments/assets/67a8c0b9-7303-4de6-825f-a5b0207450dc)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

 ![IMG-20250503-WA0020](https://github.com/user-attachments/assets/d4fccaaa-3a95-497d-ac35-a6710a325140)


![IMG-20250503-WA0019](https://github.com/user-attachments/assets/42ea741e-dffa-4e80-81e9-fd97315e41fd)



## Output
#### 1. Transient Analysis Output:

![IMG-20250503-WA0018](https://github.com/user-attachments/assets/da0fedea-80aa-4db6-aa96-aaff50c36ff6)


   ![IMG-20250503-WA0017](https://github.com/user-attachments/assets/1d1f22cd-0931-402a-a2c9-2037b2c7ed61)



## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


