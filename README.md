# Adaptive-Optics (ML-Optimized SMA–Kapton Deformable Mirror for Wavefront Correction)
Design and simulation of a thermally actuated deformable mirror using Kapton Polyimide and Shape Memory Alloy (SMA) materials. The mirror is engineered for precise wavefront correction in optical systems.

<img width="1099" height="598" alt="image" src="https://github.com/user-attachments/assets/266b9d42-3042-4209-8e1a-81eace607e01" />

##  Overview

This project focuses on the design, modeling, and machine learning-based optimization of an SMA–Kapton bimorph deformable mirror actuator for adaptive optics applications.

The actuator's thermally induced deformation is modeled to enable wavefront correction for dominant Zernike aberration modes.

##  Objectives

- Design and model an SMA–Kapton bimorph actuator using **PTC Creo**.
- Investigate thermally induced deformation for adaptive optics.
- Develop an **Elastic Net regression model** to predict actuator responses.
- Address actuator nonlinearities and coupling effects.
- Evaluate ML-based wavefront correction performance.

##  Tools & Technologies

- **PTC Creo** – 3D modeling and actuator design
- **Python / Machine Learning** – Elastic Net regression
- **Zernike Polynomials** – Wavefront aberration representation
- **Simulation-Based Validation** – Correction performance analysis

##  Aberration Modes

The model was developed for the following dominant Zernike aberration modes:

- Tilt-X
- Tilt-Y
- Power
- Astigmatism-X

##  Results

The simulated ML-based wavefront correction achieved:

| Aberration Mode | Correction Efficiency |
|---|---:|
| Tilt-X | 100% |
| Tilt-Y | 100% |
| Power | 99.5% |
| Astigmatism-X | 90% |

The results demonstrate improved correction accuracy compared with conventional control approaches.

##  Key Contributions

- Developed a CAD model of an SMA–Kapton bimorph deformable mirror actuator.
- Applied Elastic Net regression for actuator response prediction.
- Incorporated nonlinear actuator behavior and coupling effects.
- Validated wavefront correction performance through simulations.

