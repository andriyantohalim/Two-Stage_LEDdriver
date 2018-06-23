# Two-Stage LED Driver with XMC1300
This repository contains the hardware design files for the Two-Stage LED Driver project.

## Introduction
Two-Stage LED driver is designed as a performance-focused LED driver due its ability to perform power factor correction and peak current mode control for improved efficiency.

There are two power converters on board, namely:
* AC/DC Boost for Power Factor Correction
* DC/DC Flyback for LED Peak Current Mode Control

Both operates in Quasi-Resonant (QR) mode switching for optimum efficiency.


## Key Features
Primary Side Regulated (PSR) with XMC1300 microcontroller from Infineon
* Quasi Resonant control + Valley Skipping for improved performance and efficiency
* Fixed ON time for Power Factor Correction
* 2-in-1 solution: both can be implemented in a single MCU
* Support of various dimming interfaces:
** DALI Communication 
** Isolated tunable-white light
** Flicker-free and smooth tuneable white light transition

## System Specifications
* Rated Power: 60W
* Input Voltage: 90Vac - 264Vac
* Output Rating: 60V, 1A
