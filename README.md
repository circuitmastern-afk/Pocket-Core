# Pocket Core

**A Pocket-Sized AI Companion**

Pocket Core is a student engineering project exploring a compact, portable AI companion built around the ESP32-S3 microcontroller.

## Project Overview

The goal is to create a small device that can connect to online AI services and provide a simple interface for interacting with an AI assistant.

## Main Components

- **ESP32-S3:** Main microcontroller with Wi-Fi connectivity.
- **INMP441 microphone:** Captures voice input.
- **SSD1306 OLED display:** Displays text and device status.
- **AHT20 sensor:** Measures temperature and humidity.

## How It Works

The ESP32-S3 is designed to connect to a Wi-Fi network and communicate with an online AI service through an API. The microphone provides audio input, the OLED displays information, and the AHT20 collects environmental measurements.

The project is currently in the PCB design stage. The schematic and PCB layout files are included in this repository for review and further development.

## Current Status

- [x] Schematic source file created
- [x] PCB layout source file created
- [ ] PCB design verification and refinement
- [ ] Firmware development
- [ ] Hardware assembly and testing

## Repository Files

- `sch_pocket-ai_2026-10-14.json` — schematic source
- `pcb_pcb_pocket-ai_2026-10-14.json` — PCB layout source

## Future Improvements

- Voice interaction with an online AI assistant
- Text responses on the OLED display
- Improved power management
- Hardware testing and enclosure design

*Pocket Core is a work in progress and has not yet been fully assembled or tested.*


<img width="1295" height="542" alt="Screenshot (181)" src="https://github.com/user-attachments/assets/9a592b3f-7cdd-474f-8df2-a833f99e2fd1" />
