# Automatic Assembly Line for Rubik's Cube Core Assembly

**A Simulated Control System for Automated Rubik's Cube Assembly**

---

## Overview

This project represents a comprehensive automation solution designed for the assembly of the core structure of a Rubik's Cube (Speedcube). The system integrates pneumatic actuation, mechanical handling, and electrical control to achieve a continuous production cycle. Developed as part of an engineering project, the design is fully simulated using advanced CAD and pneumatic simulation tools.

---

## Project Description

The assembly line is responsible for:
- **Processing and Assembly:** Handling and positioning the central core and center pieces to form the Rubik's Cube.
- **Pneumatic Actuation:** Utilizing 11 pneumatic actuators (7 double-acting cylinders, 2 rotary actuators, and 2 pneumatic grippers) that operate in a precise sequence.
- **Sequenced Operation:** Coordinating two intermittent conveyors for the delivery of cube cores and center pieces, triggered by a start button and managed via sensor signals.
- **Quality Assurance:** Ensuring each assembly phase is verified by proximity and limit sensors, guaranteeing proper sequencing and safe operation.

---

## System Architecture

- **Pneumatic Circuit & Control:**  
  The circuit is engineered for sequential actuation of multiple pneumatic components. Detailed diagrams (Grafcet and phase movement) illustrate the control logic, fault detection, and safety mechanisms.

- **CAD Modeling:**  
  The design was developed using Creo, resulting in a detailed CAD model of the assembly line. This model provides a visual representation of the machine’s layout and components.

- **Simulation:**  
  The pneumatic circuit and operational phases were simulated using Fluidsim to validate the system's performance and reliability before physical implementation.

---

## Visual Documentation

### CAD Model

Below is an image of the CAD model representing the layout and components of the automatic assembly line:

![CAD Model](./images/cad_model.png)
*Replace this placeholder with your actual CAD model image.*

### Automatic Line Visualization Video

Watch the YouTube video demonstrating the operation of the automatic assembly line:

[![Automatic Assembly Line Video](https://img.youtube.com/vi/YourVideoLinkHere/0.jpg)](https://youtu.be/YourVideoLinkHere)
*Replace `YourVideoLinkHere` with the actual YouTube video ID or URL.*

---

## Project Phases

1. **Phase 0:** Identification of an automated section featuring at least three pneumatic actuators.
2. **Phase 1:** Creation of a schematic overview using images, videos, CAD diagrams, or animations for a clear explanation of the system.
3. **Phase 2:** Development of the Grafcet diagram and movement-phase analysis, including signal and sensor evaluations.
4. **Phase 3:** Design and documentation of the pneumatic circuit, with explanations supported by drawings or animations.
   - **Phase 3bis (Optional):** Simulation of the pneumatic circuit.
5. **Phase 4 (Optional):** Dimensioning of the pneumatic components, including air consumption calculations.

---

## Additional Information

The automatic assembly line was designed and produced by **LIYUAN Automation Equipment Technology Co. Ltd.**  
Visit their website for more details: [www.0769liyuan.com.cn](http://www.0769liyuan.com.cn)

## Author

**Simone Utili**  
*Engineering Project – Automation and Control*  
*Academic Year 2023-2024*
