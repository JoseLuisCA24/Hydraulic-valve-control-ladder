PLC Ladder Logic Control for a 3-Position Hydraulic Valve using Siemens TIA Portal

This project implements a Ladder Logic program developed in Siemens TIA Portal for a Siemens S7-1200 PLC, specifically the CPU 1215C DC/DC/DC.

The system controls and monitors a hydraulic directional valve with three mechanical positions and three output channels, including a shared general output.

Each valve position is supervised using sensor feedback to verify that the correct outputs are activated:

Position 1: Output A and the general output must be active.

Position 2: Output B and the general output must be active.

Position 3: No outputs must be active.

If the detected outputs match the expected condition, a green LED indicator is turned on to inform the operator that the valve is operating correctly.

If any incorrect output combination is detected by the sensors, the system automatically stops the operation and immediately activates a red LED warning indicator, alerting the operator to a fault condition.

This project was designed for educational and industrial automation practice, focusing on safety logic, fault detection, and operator feedback.
