# 🐞 Mayflies Population Model (Bifurcation Analysis)

## Overview

This project explores a mathematical model for population dynamics using the **Mayflies population model**, which is a variation of the logistic growth equation.

The goal is to analyze how population behavior changes over time based on different parameters and initial conditions.

---

## Model

The population evolves according to:

$$
y_n = b(1 - y_{n-1}) y_{n-1}
$$

Where:

* ( y_n ) = population at time ( n )
* ( b ) = growth parameter (controls system behavior)

---

## What I Did

* Implemented the population model using Python

* Simulated population growth over time

* Analyzed behavior for different:

  * Initial populations
  * Values of parameter ( b )

* Generated:

  * Population vs time plots
  * **Bifurcation diagrams**

---

## Key Observations

* For smaller values of ( b ), the system stabilizes

* As ( b ) increases, the system shows:

  * Period doubling
  * Chaotic behavior

* Around certain values (e.g., ~2.7+), the model becomes highly sensitive to initial conditions

---

## Tech Used

* Python
* NumPy
* Matplotlib

## Notes

* This project focuses on understanding nonlinear dynamics and chaos
* The bifurcation diagrams help visualize how system behavior changes with parameters

---

## Author

Himanshu Rathi
