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
- **Accessible** - Consideration is taken to reduce any friction from sourcing hardware to assembling an AERIS unit. The device can also operate stand-alone without the need for a home assistant instance.

<br/>

## ⚙️ Building An AERIS Unit ⚙️
<details>
<summary>Sourcing Parts</summary>
  <br/>
  
  > An up-to-date BOM with sourcing links can be found on [this](https://docs.google.com/spreadsheets/d/1mJc1zBeTynDavnT_W-ohvICVWmxclnV7TeTP1ajoJcM/edit?usp=sharing) shared Google Sheets (This is a view-only access link; save your own copy if you wish to make edits). On here you'll find cost estimates for parts, along with several locations to source them from.
  
</details>

<details>
<summary>Printing The Case</summary>
  <br/>
  
  > The STLs for the case can be found on this repo **here**. Alternatively, you can find the STLs along with print files on **Printables** and **Makerworld**.

</details>

<details>
<summary>Assembly</summary>
  <br/>
  
  > For information on building an AERIS unit and flashing the relevant firmware, view **this** section of the documentation

</details>
