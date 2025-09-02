<img width="1280" height="320" alt="image" src="https://github.com/user-attachments/assets/282ac998-404a-4882-8bfc-ee642892d781" />

# <img src="Images/favicon.png" width="32" align="absmiddle"/> AERIS – Air Quality Monitoring System <img src="Images/favicon.png" width="32" align="absmiddle"/>

[![GitHub Release](https://img.shields.io/github/release/Alexander-T-Moss/AERIS?include_prereleases=&sort=semver&color=blue)](https://github.com/Alexander-T-Moss/AERIS/releases/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](#license)
[![Issues - AERIS](https://img.shields.io/github/issues/Alexander-T-Moss/AERIS)](https://github.com/Alexander-T-Moss/AERIS/issues)
[![Platform: ESP32](https://img.shields.io/badge/Platform-ESP32-blue.svg)](https://www.espressif.com/)

**AERIS** is an open-source air quality monitor built around an **ESP32** microcontroller, **SEN55** module and custom breakout board. It measures and reports environmental parameters, such as particulate matter, VOCs, humidity and temperature in real-time to either a Home Assistant instance (through ESPHome) or a local web app.

<br/>

## Project Goals
- **Accurate & Trustable Data** – Obtained by using the factory-calibrated SEN55 and thermally isolating the unit from the other electronics.
- **Low-Cost** – AERIS' DIY-friendly design approach and BOM considerations result in a unit cost that is more than halved when compared to equivalent off-the-shelf products, at only £35/€40/$48.
- **Full Hardware Utilisation** –  Using any of the provided firmware options, every last bit of information is extracted from AERIS, getting the most "bang-for-buck" out of the used hardware.
- **Simple Assembly** – From a snap-fit case to a breakout PCB, assembly is streamlined to require minimal tools and only a few minutes.
- **Accessible Project** - Care is taken to decrease friction from obtaining hardware to building an AERIS device. Unlike other monitors, AERIS can be used fully as a standalone unit without needing a Home Assistant instance. 

<br/>

## Feature List
<details>
<summary><b>Comprehensive Sensor Array</b></summary>
<br/>

- Temperature
- Relative Humidity
- Absolute Humidity (Approximation)
- VOC Index
- Particulate Matter
  - PM1.0
  - PM2.5
  - PM4.0
  - PM10.0
- Nitrogen Oxide Index (NOx)
- Carbon Dioxide (w/ Add-On Board)
- Atmospheric Pressure (w/ Add-On Board)

</details>

<details>
<summary><b>ESPHome Integration</b></summary>
<br/>  
Requires a Home Assistant instance; alternatively, AERIS can be operated without Home Assistant through its standalone mode.
<br/>
<br/>
</details>

<details>
<summary><b>Standalone Mode</b></summary>
<br/>
The ESP controller can host a local webpage, circumventing the need for a Home Assistant instance.
<br/> 
<br/>
</details>

<details>
<summary><b>1.54" OLED Display</b></summary>
<br/>
Configurable to either show key data at a glance or show in-depth information reported by AERIS.
<br/> 
<br/>
</details>

<details>
<summary><b>Snap-Fit Case</b></summary>
<br/>
For an easy assembly, reduced BOM and clean finish, the case is designed to snap-fit together.
<br/>
<br/>
</details>

<br/>

## More Information
Interested in this project or building an AERIS unit? Visit the [official documentation](https://aeris-docs.xyz) site for more info.
