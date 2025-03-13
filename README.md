# ACMR Snake Robot - CoppeliaSim Simulation  

This project simulates an **Articulated Continuous Modular Robot (ACMR)**, a snake-like robot in **CoppeliaSim**. The robot uses **sinusoidal motion** to achieve forward movement, mimicking biological snake locomotion.

---

## **Mathematical Model**
### **Sinusoidal Motion Equation**  
The ACMR snake robot moves using a **traveling wave** along its body, defined by the equation:

$$
S_i = A \sin(2\pi f t - i \cdot \text{lag})
$$

Where:  
- \( S_i \) = **Joint position** of the \( i^{th} \) vertical joint  
- \( A \) = **Amplitude** of oscillation (5 rad)  
- \( f \) = **Frequency** of oscillation (0.01 Hz)  
- \( t \) = **Simulation time**  
- \( \text{lag} \) = **Phase difference** between consecutive joints  

Each joint follows this **sinusoidal wave**, creating a **continuous undulating motion** that propels the robot forward.

---
