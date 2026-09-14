# Transmitter

Transmitter based on ESP32 and ESPNOW for a RC tracked vehicle. It utilizes the TI BQ24075 IC for power management, so the transmitter can switch between the battery as a power supply and the usb-c connector. It used the NCV68261 for reverse current and reverse polarity protection.

## Hardware overview

- **MCU:** ESP32-S3-WROOM-1
- **Power management:** TI BQ24075 for switching between battery and USB-C power.
- **Protection:** NCV68261 for reverse current/polarity protection
- **Regulator:** TLV75533 LDO, 3.3V rail
- **Input:** push buttons for vehicle control
- **Connectivity:** USB-C (USB 2.0) for charging/data, plus a header reserved for a display


Schematic:
<img width="1271" height="636" alt="image" src="https://github.com/user-attachments/assets/f7fbc3f1-0cbd-43b7-9313-1b6d5fd95cb2" />

PCB:
I am still working on the PCB
