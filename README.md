# Mixed Analog/Digital ASIC Emulator with PLL and Power Integrity Optimization

This repository highlights the design, implementation, and optimization of a mixed analog/digital ASIC emulator. The project focuses on precision voltage monitoring, PLL stability enhancement, and power integrity validation to ensure robust performance under varying conditions.


- **Input Voltage Monitoring**: 
  - Designed precision window comparators using LTspice.
  - Achieved <1% error across ±5% input tolerances, ensuring stability across five distinct input ranges.

- **PLL Optimization**: 
  - Implemented a discrete PLL with a second-order loop filter.
  - Achieved a lock time of 1.61ms and reduced jitter to 0.155%.
  - Verified signal integrity using HyperLynx simulations.

- **Power Integrity Validation**: 
  - Simulated voltage dips/spikes (±10ns) and optimized decoupling capacitors to mitigate droop.
  - Maintained stable outputs under variable load conditions.
