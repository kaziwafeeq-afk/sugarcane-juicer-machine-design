# Design and Analysis of a Conventional Sugarcane Juicer Machine

A comprehensive machine design, MATLAB-automated calculations, and ANSYS structural analysis project for a commercial sugarcane juicer system.

---

## Project Overview
* **Objective:** Design and validate a compact, efficient roadside sugarcane juicer machine capable of handling commercial daily workloads.
* **Core Systems:** Electric motor drive (1.4 HP, 630 rpm), multi-stage pulley and gear reduction systems, crushing rollers, and a structural support frame.
* **Key Tools:** SolidWorks (CAD modeling), ANSYS (Static Structural FEA), MATLAB (Automated Gear Design and Calculations).

---

## Key Specifications & Performance
* **Machine Dimensions:** Height: 1.2 m, Breadth: 0.35 m, Length: 0.5 m.
* **Capacity & Yield:** Processes 20 kg/hour with an average juice yield of 250 ml/kg.
* **Daily Throughput:** Estimated output of 98 cups (24.5 liters) over a 7 hour working day at 70% operational efficiency.

---

## Engineering Methodology

1. **Power Transmission & Layout:**
   * Designed a multi-stage reduction using a 3-phase electric motor connected via pulley systems and gear trains (spur and pinion gears) to achieve high crushing torque at the rollers.
   * Developed automated MATLAB scripts to handle iterative gear sizing, module calculations, and stress validations without manual hand-calculation bottlenecks.

2. **Structural & FEA Analysis (ANSYS):**
   * Conducted static structural analyses on the structural steel side walls, gear teeth, and roller shafts under simulated loading and motor torque moments.
   * **Factor of Safety (FOS):** Maintained robust safety margins across components (e.g., FOS of 5.57 on the main support structure and 15 on gear/pulley subcomponents under exaggerated peak loads).

---

## Assembly Render

![Sugarcane Juicer CAD Assembly](./CAD.png)

---

## Documentation & Repository Structure
* **[Download & View Full Project Report (PDF)](./DMS%20ASSIGNMENT%201-1.pdf)**: Complete documentation including detailed calculations, BOM, and ANSYS stress/deformation contour plots.
* `CAD.png`: Isometric assembly render of the machine.
