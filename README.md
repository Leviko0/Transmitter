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
<img width="1306" height="650" alt="image" src="https://github.com/user-attachments/assets/e3fbd3e0-421d-4b72-9ad8-9240a4e5cede" />



PCB:
<img width="1408" height="540" alt="image" src="https://github.com/user-attachments/assets/8427e556-f99c-44fc-a645-615fe01363b8" />


3D view:
<img width="859" height="308" alt="image" src="https://github.com/user-attachments/assets/97b72c28-3a41-4f8f-8494-a52c517ead03" />
