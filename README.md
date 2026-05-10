## Hardware Model of Series RLC Resonant Circuit

A compact **educational hardware model** that demonstrates **Series RLC resonance** by selecting different capacitor values using toggle switches and observing how **resonant frequency, impedance, current, voltage magnification, and power factor** vary with frequency.

---

## Project Snapshot

- **Project Title**: Hardware Model of Series RLC Resonance Circuit  
- **Type**: Hardware / AC Circuits / Resonance Demonstration  
- **Core Idea**: Build a practical Series RLC setup and study resonance under different capacitor configurations.

---

## Circuit Diagram

![Circuit Diagram](Circuit%20Diagram.png)

---

## Hardware Image

![Hardware Model](Hardware%20Image.png)

---

## Description

This project focuses on the design and development of a **Hardware Model of Series RLC Resonance Circuit** for studying resonance characteristics in AC electrical circuits. The setup demonstrates the practical behavior of **resistor (R), inductor (L), and capacitor (C)** combinations under varying frequency conditions.

Using **switch-selectable capacitor values**, the model helps analyze and visualize:

- **Resonant frequency**
- **Impedance variation with frequency**
- **Current behavior (maximum at series resonance)**
- **Voltage magnification across L and C**
- **Power factor characteristics**
- **Selective frequency response**

This model is designed as an educational and experimental platform for understanding resonance phenomena used in **communication systems, filters, tuning circuits, wireless power transfer, and power electronics**.

---

## Objectives

- Develop a practical hardware model of a **Series RLC resonance** circuit  
- Study resonance characteristics under **varying capacitance values**  
- Determine **resonant frequency experimentally**  
- Analyze **current, voltage, and impedance** behavior at and around resonance  
- Demonstrate **voltage magnification** and **frequency selectivity**  
- Understand practical applications of resonance in electrical/electronic systems  

---

## Specifications (Actual Values Used)

- **Resistance (R)**: **100 Ω, 25 W**
- **Inductance (L)**: **1.79 H**
- **Capacitor options (switch-selectable)**:
  - **C1 = 2.0 µF**
  - **C2 = 2.25 µF**
  - **C3 = 2.5 µF**
  - **C4 = 4.0 µF**

> If you want, I can also add a clean “expected resonance frequency per capacitor” section.  
> (I can compute it instantly if you tell me the frequency unit/range you used in your lab—Hz/kHz—and whether your inductor is ideal or has measured series resistance.)

---

## Components Used (BOM)

Based on your uploaded BOM:

- **Inductor (1.79 H)**: Provides inductive reactance  
- **Capacitors (2 µF, 2.25 µF, 2.5 µF, 4 µF)**: Provide capacitive reactance  
- **Resistor (100 Ω, 25 W)**: Controls current and damping  
- **Toggle switches**: Used for capacitor selection  
- **AC supply terminals**: Input power supply connection  
- **Ammeter terminals**: Current measurement  
- **Connecting wires**: Circuit interconnections  
- **PCB / mounting board**: Mechanical support for hardware setup  
- **Output terminals**: Voltage and measurement points  

---

## Mathematical Background (Series RLC Resonance)

Resonance occurs when **inductive reactance equals capacitive reactance**.

### Inductive Reactance
\[
X_L = 2\pi f L
\]

### Capacitive Reactance
\[
X_C = \frac{1}{2\pi f C}
\]

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

The developed hardware model consists of an inductor, resistor, multiple capacitors, switch arrangements, and measurement terminals mounted on a compact experimental board.

- Toggle switches select different capacitor
