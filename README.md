# LabVIEW Temperature Conversion Simulation

A Virtual Instrument (VI) application designed in LabVIEW to execute and visualize bidirectional temperature conversions between Fahrenheit and Celsius scales in real time. The system couples a graphical user interface (Front Panel) with deterministic arithmetic logic data pipelines (Block Diagram).

---

## Conversion Logic Formulas

The application maps data wires across low-level execution nodes to solve standard thermodynamic scaling functions:

1. **Fahrenheit to Celsius ($F \rightarrow C$):**
   $$C = \frac{5}{9} \times (F - 32)$$

2. **Celsius to Fahrenheit ($C \rightarrow F$):**
   $$F = \left(\frac{9}{5} \times C\right) + 32$$

---

## Technical Features & UI Assets

- **Dual-Panel Workspace View**: Fully mapped layout partitioning control inputs from processing math wires (`Ctrl + T` split view).
- **Interactive Controls**: Utilizes user-adjustable sliders for fluid manual input variations.
- **Visual Thermometer Indicators**: Maps numeric floating-point values directly to visual thermometer bar gauges for direct scale tracking.
- **Strict Data Typing**: Relies on color-coded floating-point data streams (Orange wires) to preserve mathematical accuracy through operators.

---

## Workspace Requirements

- **Software Environment**: National Instruments LabVIEW (2020 or newer recommended).
- **Toolkits**: Base Core LabVIEW Package (No external hardware module dependencies required).

---

## Local Simulation Setup

### Need
To clone, execute, and dynamically adjust temperature thresholds inside a local LabVIEW engineering instance.

### Execution
1. Clone this repository to your local directory:
   ```bash
   git clone [https://github.com/som-anshu/labview-temperature-converter.git](https://github.com/som-anshu/labview-temperature-converter.git)
