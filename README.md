# Thermofluids Exam Preparation

This repository contains study materials for the Thermofluids module exam. Below are some key concepts and example questions to help you prepare.

## Table of Contents
1. [Carnot Cycle](#carnot-cycle)
2. [Bernoulli's Equation](#bernoullis-equation)

## Carnot Cycle

The Carnot cycle is a theoretical thermodynamic cycle that provides the maximum possible efficiency that a heat engine can achieve. It consists of four reversible processes: two isothermal and two adiabatic.

### Processes
1. **Isothermal Expansion (A → B):**
   - Occurs at a constant temperature $T_H$.
   - The gas absorbs heat $Q_H$ from a hot reservoir and expands.

2. **Adiabatic Expansion (B → C):**
   - No heat exchange occurs (Q = 0).
   - The temperature of the gas drops from $T_H$ to $T_C$.

3. **Isothermal Compression (C → D):**
   - Occurs at a constant temperature $T_C$.
   - The gas releases heat $Q_C$ to a cold reservoir.

4. **Adiabatic Compression (D → A):**
   - No heat exchange occurs (Q = 0).
   - The temperature of the gas increases from $T_C$ to $T_H$.

### Diagrams

#### P-V Diagram
![P-V Diagram](path/to/your/p-v-diagram.png)

#### T-S Diagram
![T-S Diagram](path/to/your/t-s-diagram.png)

### Efficiency Calculation
The efficiency of a Carnot cycle is given by:

$$
\eta = 1 - \frac{T_C}{T_H}
$$

where:
- $T_H$ is the temperature of the hot reservoir.
- $T_C$ is the temperature of the cold reservoir.

**Example Calculation:**
Given $T_H = 500\,K$ and $T_C = 300\,K$:

$$
\eta = 1 - \frac{300}{500} = 1 - 0.6 = 0.4 \text{ or } 40\%
$$

## Bernoulli's Equation

Bernoulli's equation describes the behavior of a fluid moving along a streamline. It states that the sum of the pressure energy, kinetic energy per unit volume, and potential energy per unit volume is constant.

### Equation

$$
\frac{v^2}{2} + gh + \frac{p}{\rho} = \text{const}
$$

where:
- $v$ is the fluid velocity,
- $g$ is the acceleration due to gravity,
- $h$ is the height above a reference level,
- $p$ is the pressure,
- $\rho$ is the fluid density.

### Example Problem

**Problem:**
Water flows through a pipe that narrows from a diameter of 0.1 m to 0.05 m. If the velocity of the water in the wider section is 2 m/s, find the velocity in the narrower section and the pressure difference between the two sections. Assume no energy losses.

**Solution:**

1. **Velocity Calculation:**
   Using the continuity equation $A_1 v_1 = A_2 v_2$:

   $A_1 = \pi \left(\frac{0.1}{2}\right)^2 = 0.00785 \, \text{m}^2$

   $A_2 = \pi \left(\frac{0.05}{2}\right)^2 = 0.00196 \, \text{m}^2$

   $0.00785 \cdot 2 = 0.00196 \cdot v_2$

   $v_2 = \frac{0.00785 \cdot 2}{0.00196} = 8 \, \text{m/s}$

2. **Pressure Difference Calculation:**
   Using Bernoulli's equation:

   $\frac{v_1^2}{2} + \frac{p_1}{\rho} = \frac{v_2^2}{2} + \frac{p_2}{\rho}$

   $\frac{2^2}{2} + \frac{p_1}{\rho} = \frac{8^2}{2} + \frac{p_2}{\rho}$

   $2 + \frac{p_1}{\rho} = 32 + \frac{p_2}{\rho}$

   $\frac{p_1 - p_2}{\rho} = 30$

   If $\rho = 1000 \ \text{kg/m}^3$:

   $p_1 - p_2 = 30 \cdot 1000 = 30000 \, \text{Pa} \text{ or } 30 \ \text{kPa}$
