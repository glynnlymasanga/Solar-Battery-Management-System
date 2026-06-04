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

<img width="1262" height="682" alt="image" src="https://github.com/user-attachments/assets/366f0fbf-8b6e-4d5b-81d9-980c2b0d8f65" />

### Cell Protection & Balancing Section

<img width="1264" height="329" alt="image" src="https://github.com/user-attachments/assets/12c49fff-41bd-4a4e-8d5b-ee6bf189c886" />

### Power Path 

<img width="1265" height="388" alt="image" src="https://github.com/user-attachments/assets/5bfa315a-f43f-455f-b5e6-084a2ae0148b" />

 ### 5V Supply

<img width="1262" height="370" alt="image" src="https://github.com/user-attachments/assets/e1779cea-af8a-4d6d-bb57-200c5a35b271" />

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


