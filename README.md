# Output Voltage Regulation of Buck Converter using Type-II Compensator

## Project Overview

This project focuses on the design, simulation, and implementation of a Type-II compensator to achieve precise output voltage regulation in a Buck converter. The Buck converter is a DC-DC converter that steps down the input voltage to a lower output voltage, widely used in power supply systems and battery chargers. The primary objective of this project is to ensure accurate tracking of the output voltage with the reference voltage while maintaining stability despite changes in load or input conditions.

## Objectives

- Design a Type-II compensator for a Buck converter.
- Achieve accurate output voltage tracking with a reference voltage.
- Ensure system stability under varying load and input conditions.
- Improve phase margin and adjust gain crossover frequency for enhanced stability.

## Project Structure

- **1. Uncompensated System Analysis**: Analyzes the open-loop Buck converter system, deriving its transfer function and simulating its performance using MATLAB. The system’s stability and frequency response are evaluated using Bode plots.
  
- **2. Compensator Design**: Involves designing a Type-II compensator to improve system stability. The compensator is designed to achieve a specific gain crossover frequency (100 Hz) and phase margin (120°). MATLAB is used to derive and simulate the compensator’s transfer function.

- **3. Closed-Loop System Implementation**: Integrates the compensator into the Buck converter’s control loop. The closed-loop system is simulated in MATLAB/Simulink to evaluate its performance under various conditions.

- **4. Simulation and Analysis**: Simulates the closed-loop system using MATLAB/Simulink, analyzing key parameters such as input voltage, output voltage, inductor current, and compensator output. The Bode plot of the compensated system is generated to confirm improvements in phase margin and stability.

- **5. Results and Conclusion**: Demonstrates the effectiveness of the Type-II compensator in stabilizing the Buck converter’s output voltage, ensuring accurate voltage regulation and improved stability.

