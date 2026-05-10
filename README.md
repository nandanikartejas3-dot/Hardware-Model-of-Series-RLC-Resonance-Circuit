## Hardware Model of Series RLC Resonant Circuit

A compact **educational hardware model** that demonstrates **Series RLC resonance** by varying capacitance using switch arrangements and observing how **resonant frequency, impedance, current, voltage magnification, and power factor** change with frequency.

---

## Project Snapshot

- **Project Title**: Hardware Model of Series RLC Resonance Circuit  
- **Type**: Hardware / AC Circuits / Resonance Demonstration  
- **Core Idea**: Build a practical Series RLC setup and study resonance characteristics under different capacitor combinations.

---

## Circuit Diagram

![Circuit Diagram](Circuit%20Diagram.png)

---

## Hardware Image

![Hardware Model](Hardware%20Image.png)

---

## Description

This project focuses on the design and development of a **Hardware Model of Series RLC Resonance Circuit** for studying resonance characteristics in AC electrical circuits. The setup demonstrates the practical behavior of **resistor (R), inductor (L), and capacitor (C)** combinations under varying frequency conditions.

The developed hardware model allows analysis of **series resonance** by selecting different capacitor configurations using switch arrangements. This helps visualize key resonance parameters such as:

- **Resonant frequency**
- **Impedance variation**
- **Current behavior**
- **Voltage magnification**
- **Power factor characteristics**
- **Selective frequency response**

This model is designed as an educational and experimental platform for understanding resonance phenomena used in **communication systems, filters, tuning circuits, wireless power transfer, and power electronics**.

---

## Objectives

- Develop a practical hardware model of **Series RLC resonance** circuits  
- Study resonance characteristics under **varying capacitance values**  
- Determine **resonant frequency experimentally**  
- Analyze **current, voltage, and impedance behavior** at resonance  
- Demonstrate **voltage magnification** and **selective frequency response**  
- Understand practical applications of resonance in electrical/electronic systems  

---

## Components Used

> (Update the exact values if you want this section to look “complete” on GitHub.)

- **Resistor (R)**: ____ Ω, ____ W  
- **Inductor (L)**: ____ H (type: ____ )  
- **Capacitors (C)**: multiple values (selectable via switches), ____ V rating  
- **Switches**: toggle/DIP for capacitor selection  
- **Measurement**: ammeter/multimeter (and DSO if available)  
- **AC Source / Function Generator**: ____  
- **Trainer board / terminals / wiring**

---

## Mathematical Background (Series RLC Resonance)

Resonance occurs when inductive reactance equals capacitive reactance.

### Inductive Reactance
\[
X_L = 2\pi f L
\]
Where:
- \(X_L\): inductive reactance  
- \(f\): supply frequency  
- \(L\): inductance  

### Capacitive Reactance
\[
X_C = \frac{1}{2\pi f C}
\]
Where:
- \(X_C\): capacitive reactance  
- \(C\): capacitance  

### Resonance Condition
\[
X_L = X_C
\]

### Resonant Frequency
\[
f_r = \frac{1}{2\pi \sqrt{LC}}
\]

### Impedance at Series Resonance
At resonance, impedance becomes minimum:
\[
Z = R
\]
So, **current becomes maximum**.

---

## How the Hardware Model Works (What You Observe)

The developed hardware model consists of an inductor, multiple capacitors, resistors, switch arrangements, and measurement terminals mounted on a compact experimental board.

- Different capacitor values can be selected using switches to **vary resonant frequency**
- Under AC supply with changing frequency, \(X_L\) and \(X_C\) interact to show resonance practically
- Ammeter terminals allow observing **current variation**, showing a clear peak at resonance
- Demonstrates **impedance variation**, **frequency selectivity**, and resonance behavior used in real circuits

---

## Experimental Results (Summary)

The developed RLC resonance model successfully demonstrated the practical behavior of the **series RLC circuit** under varying capacitance conditions.

At resonance frequency:
- \(X_L\) and \(X_C\) become equal  
- Circuit impedance becomes minimum  
- Current shows a distinct maximum value  

---

## Conclusion

The **Hardware Model of Series RLC Resonance Circuit** successfully demonstrated resonance phenomena in AC circuits and validated theoretical concepts through practical experimentation.

This project enhanced understanding of:
- **Resonant frequency**
- **Impedance variation**
- **Maximum current at series resonance**
- **Frequency-selective behavior**
- Real-world usage in **tuning circuits, filters, communication systems, wireless power transfer, and power electronics**

---

## References

1. B. L. Theraja & A. K. Theraja, *Electrical Technology – AC Circuits*, S. Chand Publications  
2. NPTEL Course Material – *Basic Electrical Circuits* by Prof. D. C. Kulshreshtha  
