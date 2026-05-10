# Hardware Model of Series RLC Resonance Circuit

This project focuses on the design and development of a **Hardware Model of Series RLC Resonance Circuit** for studying resonance characteristics in AC electrical circuits. The setup demonstrates the practical behaviour of **resistor (R)**, **inductor (L)**, and **capacitor (C)** combinations under varying frequency conditions.

The hardware model allows analysis of **series resonance** by selecting different capacitor configurations using switch arrangements. It helps visualize important resonance parameters such as resonant frequency, impedance variation, current behaviour, voltage magnification, and power factor characteristics.

The model was designed as an **educational and experimental platform** for understanding resonance phenomena widely used in communication systems, filters, tuning circuits, wireless power transfer, and power electronics applications.

![Hardware Model](hardware-model-photo.png)

---

## Objectives

- Develop a practical hardware model of Series RLC resonance circuits
- Study resonance characteristics under varying capacitance values
- Determine resonant frequency experimentally
- Analyse current, voltage, and impedance behaviour at resonance
- Demonstrate voltage magnification and selective frequency response
- Understand practical applications of resonance in electrical and electronic systems

---

## Components Used

| Component | Specification / Details |
|-----------|------------------------|
| Inductor (L) | Fixed inductance coil |
| Capacitors (C) | Multiple values (selectable via switches) |
| Resistor (R) | Fixed resistance element |
| Toggle Switches | For capacitor selection |
| Ammeter Terminals | For current measurement |
| AC Supply Terminals | Input supply connection |
| Experimental Board | Compact mounted base panel |
| Connecting Wires | For circuit interconnections |

---

## Circuit Diagram

![Circuit Diagram](circuit-diagram.png)

---

## Mathematical Background

The resonance condition occurs when inductive reactance becomes equal to capacitive reactance in an AC circuit.

### Inductive Reactance

$$X_L = 2\pi f L$$

| Symbol | Meaning |
|--------|---------|
| $X_L$ | Inductive reactance (Ω) |
| $f$ | Supply frequency (Hz) |
| $L$ | Inductance (H) |

### Capacitive Reactance

$$X_C = \frac{1}{2\pi f C}$$

| Symbol | Meaning |
|--------|---------|
| $X_C$ | Capacitive reactance (Ω) |
| $f$ | Supply frequency (Hz) |
| $C$ | Capacitance (F) |

### Resonance Condition

At resonance:

$$X_L = X_C$$

Therefore:

$$2\pi f L = \frac{1}{2\pi f C}$$

The **resonant frequency** is:

$$f_r = \frac{1}{2\pi\sqrt{LC}}$$

### Impedance Behaviour

**Series Resonance:**
At resonance, circuit impedance becomes **minimum**:

$$Z = R$$

- Current becomes **maximum**
- $X_L$ and $X_C$ cancel each other out
- Power factor = 1 (purely resistive)

---

## How It Works

1. The hardware board contains an **inductor**, **multiple capacitors**, and **resistors** mounted on a compact experimental panel.
2. Different capacitor values can be selected using **toggle switches** to vary the resonant frequency of the circuit.
3. The inductive and capacitive reactances interact with each other under **AC supply conditions** to demonstrate resonance behaviour practically.
4. **Ammeter terminals** are included for observing current variation at resonance.
5. At resonance, the setup demonstrates:
   - Maximum current flow in series resonance
   - Minimum impedance ($Z = R$)
   - Frequency-selective behaviour
   - Voltage magnification across L and C

---

## Hardware Overview

The developed hardware model consists of:
- An **inductor**, multiple **capacitors**, and **resistors**
- **Switch arrangements** for selecting capacitor combinations
- **Measurement terminals** for voltage and current observation
- All components mounted on a **compact experimental board**

---

## Experimental Results

- The model successfully demonstrated the practical behaviour of a series RLC circuit under varying capacitance conditions.
- At resonance frequency, inductive reactance and capacitive reactance became equal, resulting in distinct impedance and current characteristics.
- Series resonance exhibited **maximum current** and **minimum impedance** at the resonant frequency.
- Different capacitor selections produced different resonant frequencies, validating the formula $f_r = \frac{1}{2\pi\sqrt{LC}}$.

---

## Conclusion

The **Hardware Model of Series RLC Resonance Circuit** successfully demonstrated the practical implementation and analysis of resonance phenomena in AC circuits. The project provided clear understanding of:

- Resonant frequency determination
- Impedance variation with frequency
- Current and voltage characteristics at resonance
- Frequency-selective behaviour in series RLC configurations

The model effectively validated theoretical resonance concepts through practical experimentation using different capacitor combinations and inductive elements. It also highlighted important applications of resonance in **communication systems, tuning circuits, filters, wireless power transfer, and power electronics**.

Overall, this project enhanced practical knowledge of AC circuit analysis, resonance theory, experimental techniques, and electrical system behaviour under varying frequency conditions.

---

## References

1. B. L. Theraja & A. K. Theraja, *Electrical Technology – AC Circuits*, S. Chand Publications.
2. NPTEL Course Material – *Basic Electrical Circuits* by Prof. D. C. Kulshreshtha.
