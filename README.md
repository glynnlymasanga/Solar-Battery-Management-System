# MPPT Solar Charger and Power Management System for 2S Li-Ion Batteries

Complete solar-powered battery charging and power management system designed around the BQ24650, BQ2920X, LTC4412, and LMR23630-Q1. Supports MPPT charging, battery protection, cell balancing, power-path control, load sharing, and regulated 5V power delivery.

## Overview

A solar-powered 2S Li-ion battery charging and power management system featuring MPPT charging, battery protection, cell balancing, load sharing, and regulated 5V power delivery for embedded applications.

## Architecture

Solar Panel → MPPT Charger → 2S Li-Ion Battery → Protection & Balancing → Power Path Controller → 5V Supply → Load

## Key Features

* 5V–28V input range
* 2S Li-Ion battery support
* 8.4V charge voltage
* 1.65A charge current
* MPPT solar charging
* CC/CV charging control
* Dynamic Power Management (DPM)
* Battery temperature monitoring
* Cell balancing and over-voltage protection
* Automatic power-path management
* Solar load sharing
* 5V auxiliary power rail

## Major Components

| Function                    | Device      |
| --------------------------- | ----------- |
| Battery Charger & MPPT      | BQ24650     |
| Cell Protection & Balancing | BQ2920X     |
| Power Path Controller       | LTC4412     |
| 5V Buck Converter           | LMR23630-Q1 |

## Design Parameters

| Parameter                   | Value     |
| --------------------------- | --------- |
| Solar Panel                 | 12V, 36W  |
| Battery Configuration       | 2S Li-Ion |
| Battery Charge Voltage      | 8.4V      |
| Battery Charge Current      | 1.65A     |
| BQ24650 Switching Frequency | 600kHz    |
| Output Voltage              | 5V        |
| Output Current              | 2A        |
| Operating Temperature       | 0°C–85°C  |

## Repository Contents

* KiCad schematics
* Design calculations
* Bill of Materials (BOM)
* Component datasheets
* Project documentation

## System Schematics

### Charger Section

<img width="3508" height="2480" alt="image" src="https://github.com/user-attachments/assets/85609985-ed2d-4687-804d-83651ab8c33b" />

### Protection & Balancing Section

<img width="978" height="322" alt="image" src="https://github.com/user-attachments/assets/25619421-3683-4384-9dc5-c110468b13c5" />

### Power Path 

<img width="977" height="465" alt="image" src="https://github.com/user-attachments/assets/007a7779-59c6-471a-8fbf-035ae1543b56" />

 ### 5V Supply

<img width="981" height="382" alt="image" src="https://github.com/user-attachments/assets/4544926b-54a7-434b-b53c-8a549b2353d2" />

## Project Status

✅ System architecture completed

✅ Component selection completed

✅ Design calculations completed

✅ Schematic capture completed

⬜ PCB layout

⬜ Hardware validation

⬜ Performance testing

## Lessons Learned

This project provided practical experience in lithium-ion battery charging, MPPT implementation, power-path management, battery protection, component selection, and power electronics system design.


