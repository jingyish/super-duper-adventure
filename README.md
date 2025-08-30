# Field-based PCB Diagnostics – BMS Testing
This board was removed from a battery energy storage system during a field inspection. I was responsible for determining whether the board was electrically damaged or could still be reused.

Continuity Testing: Using a multimeter in continuity mode, I tested:

Power input path (DC+ / DC- across connectors and fuses)
Relay drive paths (signal pin to coil terminals)
Voltage output pins and protection diodes
Decision Criteria:

If power input trace was broken or a fuse was open, the board was rejected.
If control signals had discontinuity from I/O connector to load components, the board was flagged for repair.
If no electrical failures were found, the board was re-qualified for reuse after cleaning and inspection.
Notes
Although I didn’t design this PCB, my experience with system-level electrical diagnostics gives me a strong practical intuition. 
