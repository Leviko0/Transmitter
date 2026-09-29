# Transmitter

Transmitter based on ESP32 and ESPNOW for a RC tracked vehicle. It utilizes the TI BQ24075 IC for power management, so the transmitter can switch between the battery as a power supply and the usb-c connector. It used the NCV68261 for reverse current and reverse polarity protection.

## Hardware overview

- **MCU:** ESP32-S3-WROOM-1
- **Power management:** TI BQ24075 for switching between battery and USB-C power.
- **Protection:** NCV68261 for reverse current/polarity protection
- **Regulator:** TPS63021 Buck-Boost, 3.3V rail
- **Input:** push buttons for vehicle control
- **Connectivity:** USB-C (USB 2.0) for charging/data, plus a header reserved for a display


Schematic:
<img width="1214" height="607" alt="image" src="https://github.com/user-attachments/assets/805673b9-ace3-439c-a04b-5473f6f95984" />



PCB:
PCB is still a work in progress

