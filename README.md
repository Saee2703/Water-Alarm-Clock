Project 1 — Water Alarm Circuit

A water detection alarm circuit built entirely from scratch in KiCad as my first complete PCB design project.

When water bridges the detection probes, it provides gate voltage to a 2N7000 N-channel MOSFET, switching it on and simultaneously activating a buzzer and LED indicator. A 1N4007 flyback diode protects the MOSFET from inductive voltage spikes generated when the buzzer deactivates. A 10kΩ gate pull-down resistor prevents false triggering from floating gate voltage. A 1nF gate capacitor provides noise filtering.

Technical deliverables: Full schematic with zero ERC errors, 2-layer PCB layout with ground plane, DRC zero errors, 3D view generated.

Tools: KiCad 8
<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/ed7520c6-20be-4507-9d27-9f9e35e480d9" />
<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/f77b3a80-1f51-42a2-a32c-33bb2f0ea2ec" />
<img width="1470" height="956" alt="Image" src="https://github.com/user-attachments/assets/d0685825-4e6f-42fa-ad09-5293e3748111" />
