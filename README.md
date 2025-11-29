
# Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---
## EQUIPMENTS REQUIRED:
Optisystem Software – OptiPerformer 22.0
---
## THEORY:

Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.
In this exercise, you will download and install OptiPerformer on your PC/laptop. Your license of OptiPerformer will be capable of loading and running OptiSystem simulations prepared for this course.
Once you have installed OptiPerformer, you can copy the first file (named: ‘Introduction_OptiPerformer.osp’) to your PC and run the simulation. The first file is a basic fiber optic system consisting of a transmitter, a fiber and a receiver. The system is “instrumented” with an optical power meter at the input to receiver (or the output of the fiber) and a bit error rate (BER) analyzer.

---
## PROCEDURE:
1.	Download and install OptiPerformer from the optiwave.com web site.
2.	Copy the ‘Introduction_OptiPerformer.osp’ file to your PC
3.	Start OptiPerformer
4.	Use either the File menu or the Open File button to open the Fiber Optic System File.
5.	Study the layout, which includes some text and boxes to identify the three components of the fiber optic system. The “transmitter” section includes a binary source (PRBS or pseudo-random bit sequence generator), an electrical pulse generator, a laser diode and an external modulator. The receiver section includes a photodiode, a low-pass filter and a decision circuit, which includes a BER analyzer. We will cover these components in more detail later in the course.
6.	Run the simulation by pushing the start button. The progress of the simulation will be displayed
and the message “Calculation Finished!” will appear when the simulation runs to completion.
7.	Double click on the optical power meter and the BER analyzer and move the windows as necessary for clarity. Check the box next to “Show Eye Diagram” in the BER window. The optical power meter shows the power at the input to the photodiode in both watts and dBm. The BER window displays the “eye diagram” and several quantities including the “Max Q
Factor” and the “Min BER”.
8.	The simulation is set to run 5 “iterations”, with the fiber length varying from 50 to 150 km in 5 steps. The index is displayed in the upper right corner of the layout. To step through the iterations, use the forward and reverse buttons in the lower left of the window. Note the change in received power and BER display (eye diagram, Q factor and BER) with fiber length.
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

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

![Exp6](https://github.com/user-attachments/assets/6397eb59-8790-4d44-9e07-32122c0fbdf1)

---

## Graphs

<img width="912" height="975" alt="Screenshot 2025-11-12 072050" src="https://github.com/user-attachments/assets/566a99a6-5102-48bc-9e9a-da70cd664c39" />

---
---

<img width="912" height="975" alt="Screenshot 2025-11-12 072143" src="https://github.com/user-attachments/assets/c07e2dac-efe7-420a-9ce3-c07f8af41f87" />

---
---

<img width="912" height="975" alt="Screenshot 2025-11-12 072251" src="https://github.com/user-attachments/assets/e25a0844-1a26-4026-aad6-9584f15d2a96" />

---
---



## RESULT

The optical communication system was successfully simulated using **OptiPerformer**.
As the **fiber length increased** from **50 km to 150 km**, the following trends were observed:

* **Received optical power** decreased due to fiber attenuation.
* **Q-factor** gradually decreased, indicating signal quality degradation.
* **Bit Error Rate (BER)** increased with distance, showing higher error probability.
* The **eye diagram** became more closed at longer fiber lengths, confirming dispersion and noise effects.

Hence, the simulation verified that **optical signal performance deteriorates with increasing fiber length** due to attenuation and dispersion losses.
