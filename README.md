Industrial Tank Level Automation & Control

🛠️ Physical Application & InstrumentationThe PLC logic is engineered to interface directly with real-world process instrumentation

Analog Sensor (Level): Ultrasonic or hydrostatic pressure level transmitter scaled from 0.0% (Empty) to 100.0% (Full).
Actuators (FillCmd / DrainCmd): Digital outputs driving the contactors for the inlet feed pump and discharge pump (or solenoids).
Operator Interface (FillButton / DrainButton): Physical, momentary Normally Open (NO) pushbuttons on the control panel.

🔒 Process Safety InterlocksAnti-Overflow Protection: An LT (Less Than) comparison block continuous monitors tank capacity, automatically breaking the fill pump's seal-in circuit exactly at 100.0% to prevent spills.
Run-Dry Pump Protection: A GT (Greater Than) block kills the discharge pump command immediately at 0.0%, preventing pump cavitation and mechanical seal damage.HMI Early Warnings: Dynamic comparators trigger critical HMI alarms for High Level (80%) and Low Level (20%) before thresholds are breached.
