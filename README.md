# H-Pulse Train controller (G4)
A advanced Electronic Speed Control intended for controlling Model trains. Though the load is simple, this ESC is equipped with the means to enable advanced monitoring/control of model trains
In the long-run the controller can be programmed to be able to communicate to digital trains via Digital-Command-Control (DCC)

# Specifications:
+ INPUT:	8-24V DC
+ OUTPUT: 8-24V <6A
+ TDP: ~1-5 Watt depending on load
+ Controller: Raspberry Pi RP2040 125Mhz Dual-core ARM microcontroller.
+ Driver: Infineon TLE9201 6A H-Bridge motor driver with SPI interface
+ Display: GC9A01 240x240 circular IPS Monitor

#Features:
+ Current Monitoring
+ Voltage Monitoring
+ Reverse Polarity Protection
+ Transient Voltage Suppression
+ Overcurrent Detection / Short-circuit protection
+ Under-voltage lockout
+ Open-load (Derail) detection
+ FAN Load switch
+ Piezo-speaker for feedback
+ Extra headers for (Matrix) IO
+ DCC-Ready Hardware

# TODO
+ Upload initial firmware
+ Improve Firmware for use of H-bridge
+ Improve graphics display desing
