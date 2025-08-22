<img width="1280" height="320" alt="image" src="https://github.com/user-attachments/assets/282ac998-404a-4882-8bfc-ee642892d781" />


# ☁️ AERIS – Air Quality Monitoring System ☁️

[![GitHub Release](https://img.shields.io/github/release/Alexander-T-Moss/AERIS?include_prereleases=&sort=semver&color=blue)](https://github.com/Alexander-T-Moss/AERIS/releases/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](#license)
[![Issues - AERIS](https://img.shields.io/github/issues/Alexander-T-Moss/AERIS)](https://github.com/Alexander-T-Moss/AERIS/issues)
[![Platform: ESP32](https://img.shields.io/badge/Platform-ESP32-blue.svg)](https://www.espressif.com/)

**AERIS** is an open-source air quality monitoring system built around the **ESP32** microcontroller and a **SEN55 sensor module**, paired with a custom breakout PCB board. It measures and reports environmental parameters, such as PM1.0, PM2.5, PM4.0, PM10, VOC, NOX, humidity and temperature in real-time to Home Assistant through ESPHome.

<br/>

## 📌 Project Goals 📌
- **Accurate & Trustable Data** – Accomplished using the SEN55, which is factor calibrated, along with thermally isolating the unit from the other electronics to prevent unwanted influence on readings.
- **Low-Cost** – Compared to similar devices, AERIS's DIY design approach and BOM minimisation considerations lead to a halving of the unit cost at just £35/€40/$48.
- **Full Hardware Utilisation** – With the provided firmware options, every last drop of information is pulled from AERIS, getting as much "bang-for-buck" out of the used hardware.
- **Simple Assembly** – From a snap-fit case to a breakout PCB, assembly is simplified to requiring minimal tools and a few minutes of time.
- **Accessible** - Consideration is taken to reduce any friction from sourcing hardware to assembling an AERIS unit. The device can also operate stand-alone without the need for home assistant.

<br/>

## 🔧 Required Hardware

| Item #  | Component        | Cost       | MOQ     | Quantity | Unit Cost  |
|---------|------------------|------------|---------|----------|------------|
| 1       | XIAO ESP32-C3/C6 | £4.40      | 1       | 1        | £4.40      |
| 2       | Sensirion SEN55  | £24.22     | 1       | 1        | £24.22     |
| 3       | Breakout PCB     | £6.30      | 5       | 1        | £1.26      |
| 4       | M3x5x4 Heatsets  | £3.05      | 1x100   | 6        | £0.18      |
| 5       | M3x6 BHCS        | £1.16      | 1x50    | 6        | £0.14      |
| 6       | JST XH 2.54 5P   | £1.41      | 1x10    | 1        | £0.14      |
| 7       | JST GH 1.25 6P   | £1.54      | 1x10    | 1        | £0.15      |
| **---** | **Total**        | **£42.08** | **---** | **---**  | **£30.31** |

## 🔧 Optional Hardware (Highly Recommended)

| Item #  | Component         | Cost      | MOQ     | Quantity | Unit Cost  |
|---------|-------------------|-----------|---------|----------|------------|
| 1       | 2507 5V Fan       | £1.64     | 1       | 1        | £1.64      |
| 2       | 1k Resistor       | £0.87     | 1x100   | 1        | £0.01      |
| 3       | 2N3904 Transistor | £1.69     | 1x100   | 1        | £0.02      |
| 4       | JST XH 2.54 2P    | £0.93     | 1x10    | 1        | £0.09      |
| **---** | **Total**         | **£5.13** | **---** | **---**  | **£1.76**  |
