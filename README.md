# Linear Control Systems (Fall 2025)
**K. N. Toosi University of Technology**

Welcome to the official GitHub repository for the Linear Control Systems course for the Fall 2025 semester. This repository serves as the central hub for all course materials, including lecture notes, assignments, code samples, and important announcements.

## Course Description

This course provides a comprehensive introduction to the analysis and design of feedback control systems. Students will learn the fundamental principles of modeling dynamic systems, analyzing their time and frequency responses, and designing controllers to achieve desired performance specifications. Topics include system representation using transfer functions and state-space models, stability analysis, root locus techniques, frequency-domain analysis (Bode and Nyquist plots), and the design of classic controllers like PID, lead, and lag compensators. The course aims to bridge the gap between theoretical concepts and practical engineering applications.

## Course Staff

| Role                      | Name                       | Contact Information                                                                                               |
| ------------------------- | -------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **Instructor** | Prof. Hamid D. Taghirad    | 📧 [taghirad@kntu.ac.ir](mailto:taghirad@kntu.ac.ir) <br> 🌐 [Website](http://aras.kntu.ac.ir/taghirad)             |
| **Head Teaching Assistant** | Mohammad Javad Ahmadi      | 📧 [mjahmadee@gmail.com](mailto:mjahmadee@gmail.com) <br> 🐙 GitHub: [@MJAHMADEE](https://github.com/MJAHMADEE) |
| **Head Teaching Assistant** | Parisa Ghorbani            | 📧 [pariis.ghorbani@gmail.com](mailto:pariis.ghorbani@gmail.com) <br> 🐙 GitHub: [@ParisaGhorbani](https://github.com/ParisaGhorbani) |

## Repository Structure

All course materials are organized into the following directories:

* **/Lectures**: Contains PDF files of lecture slides for each week.
* **/Assignments**: Programming assignments, problem sets, and their due dates.
* **/Solutions**: Solutions to selected problems and assignments (will be posted after the deadline).
* **/Code**: MATLAB and Simulink examples used in lectures and assignments.
* **/Templates**: Standard templates for reports and README files for your projects.
* **/Announcements**: Important updates and announcements regarding the course.

## Prerequisites

* Differential Equations
* Laplace Transforms
* Complex Variables
* Basic Linear Algebra

## Required Software

* **MATLAB** & **Simulink** (Control System Toolbox is essential)

---

## Course Schedule

| Week | Topic                                   | Key Concepts                                                                                                                              |
| :--: | --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
|  01  | **Introduction: Why Feedback?** | Conceptual & physical components of feedback systems, properties of feedback: stability, tracking, disturbance rejection, noise reduction, desensitization. |
|  02  | **System Representation** | Laplace Transform, transfer function models, block diagrams & simplification, Signal Flow Graphs (SFG), Mason's Gain Formula, DC motor modeling, state-space representation. |
|  03  | **Time Response of Linear Systems** | Impulse & step response, first & second-order system characteristics, rise time, settling time, overshoot, steady-state error, decay ratio, time-domain vs. frequency-domain. |
|  04  | **Stability Analysis** | Bounded-Input, Bounded-Output (BIBO) stability, characteristic polynomials, system poles, Routh-Hurwitz stability criterion. |
|  05  | **The Root Locus Method, Part 1** | Relationship between closed-loop poles and loop gain, graphical method for plotting pole locations, magnitude and angle conditions. |
|  06  | **The Root Locus Method, Part 2** | Rules for sketching the root locus, gain selection, static feedback design, desired performance characteristics. |
|  07  | **Root Locus-Based Controller Design** | Effects of adding poles and zeros, design of Proportional (P), Proportional-Derivative (PD), Lead, and Lag compensators using the root locus. |
|  08  | **Frequency Response Analysis, Part 1** | Bode plots, Bode's gain-phase relationship, crossover frequency, sketching Bode plots for first/second-order, unstable, and non-minimum phase systems. |
|  09  | **Frequency Response Analysis, Part 2** | Nyquist plots, mapping from Bode to Nyquist, conformal mapping, Cauchy's argument principle, the Nyquist contour, Nyquist stability criterion. |
|  10  | **Frequency Response Analysis, Part 3** | Handling poles/zeros on the imaginary axis, relationship between Bode and Nyquist plots, counting encirclements and closed-loop poles. |
|  11  | **Frequency-Domain Specifications** | Resonant peak, resonant frequency, bandwidth, gain and phase crossover frequencies, roll-off rate, frequency response of second-order systems. |
|  12  | **Dynamic Feedback Design** | Stability margins (gain and phase margin), reading margins from Bode plots, Nichols charts, M-circles, sensitivity and complementary sensitivity functions. |
|  13  | **Dynamic Compensator Design** | Designing P controllers for stability margins, Lead/PD design for bandwidth compensation, Lag/PI design for steady-state error and disturbance rejection, Lead-Lag and PID controller design. |
|  14  | **Sensitivity-Based Controller Design** | The sensitivity function and its complement, shaping desired sensitivity functions, causality constraints, the interpolation conditions theorem, design for unstable and non-minimum phase systems. |

---

## How to Get Help

* For questions about lecture content or assignments, please **open an issue** in this repository. This allows everyone to benefit from the discussion.
* For personal matters or grade inquiries, please email one of the Teaching Assistants.

## License

The content of this repository is licensed under the [MIT License](LICENSE.md), which allows for reuse and distribution with attribution.
