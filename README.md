
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
| ---- | ----------------- | --------------------- | ------------------- | ------------ | ------- | ---------- | ---------------------------------- |
| 1    | 106               | 3.615 × 10⁻⁶          | -24.148             | 37.255       | 0       | 0.546875   | 7.203894 × 10⁻⁶                    |
| 2    | 107               | 3.996 × 10⁻⁶          | -24.690             | 37.384       | 0       | 0.546875   | 6.7642 × 10⁻⁶                      |
| 3    | 108               | 3.297 × 10⁻⁶          | -24.818             | 36.3221      | 0       | 0.546875   | 6.8790 × 10⁻⁶                      |
| 4    | 109               | 3.149 × 10⁻⁶          | -25.018             | 35.3584      | 0       | 0.546875   | 6.07846 × 10⁻⁶                     |
| 5    | 110               | 2.950 × 10⁻⁶          | -25.28              | 37.4011      | 0       | 0.546875   | 5.83215 × 10⁻⁶                     |

---

## Graphs

<img width="1002" height="641" alt="image" src="https://github.com/user-attachments/assets/5d8ef5d6-ebfc-42ce-af70-97589bc1c745" />
<img width="495" height="299" alt="image" src="https://github.com/user-attachments/assets/800c6f5d-80a0-4ec3-97c9-0d38524a0beb" />



## RESULT

*(Summarize key findings from simulation and analysis)*
