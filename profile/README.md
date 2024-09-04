# Vortex-01 Project

[![pt-BR](https://img.shields.io/badge/lang-pt--BR-green.svg)](https://github.com/Vortex-01/.github/blob/main/README.pt-BR.md)
[![es](https://img.shields.io/badge/lang-es-red)](https://github.com/Vortex-01/.github/blob/main/README.es.md)
[![fr](https://img.shields.io/badge/lang-fr-blue)](https://github.com/Vortex-01/.github/blob/main/README.fr.md)
[![ru](https://img.shields.io/badge/lang-ru-yellow.svg)](https://github.com/Vortex-01/.github/blob/main/README.ru.md)

## Objective
To create a low-cost satellite, called Vortex-01, that provides free Wi-Fi via a satellite connection. The satellite will be equipped with sensors, power systems, a strong RF transmitter, and a remote security system.

## Satellite Specifications

- **Name:** Vortex-01
- **Function:** Provides free internet via satellite

### Main Components

- **Raspberry Pi 4B:** Central computer for data processing, control, and managing communication protocols (including RF signal transmission).
- **RF Transmitter:** **HackRF One** or similar, capable of broadcasting at high power across a wide frequency range. This will be used to transmit RF signals that can be captured by antennas on Earth.
- **Antennas (for RF transmission):** Combination of Yagi or Dipole antennas to maximize signal strength and reach.
  
### Internet Distribution System

1. **RF Signal Transmission:**
   - The satellite will transmit internet data over RF frequencies (2.4GHz or 5GHz bands are most common for Wi-Fi, but you may choose other frequencies depending on regulations and range).
   - The **HackRF One** is a software-defined radio (SDR) capable of transmitting and receiving RF signals across a broad frequency range. It will be connected to the Raspberry Pi, which will handle the modulation of internet data into the RF signal.
   
2. **Earth-based Conversion (RF to Wi-Fi):**
   - People on Earth will need a directional antenna (like a Yagi) to receive the RF signal. Once captured, the signal will pass through a **Software Defined Radio (SDR) receiver**, such as **RTL-SDR**.
   - A converter device (potentially a Raspberry Pi or a Wi-Fi router with firmware modifications) will demodulate the RF signal and convert it into a standard Wi-Fi signal (802.11 standards) that can be accessed by devices such as smartphones and laptops.

### Sensors

- **Atmospheric Pressure Sensor:** **BMP180** - Affordable sensor for measuring pressure and altitude.
- **Acceleration Sensor (IMU):** **MPU-6050** - Combines accelerometer and gyroscope, ideal for monitoring movement and orientation.
- **Radiation Sensor:** **RADFET** - Optional, for cost-effective monitoring of radiation exposure.

### Antennas

- **Broadband Dipole Antenna:** Low-cost homemade dipole antenna for RF communication.
- **Yagi Antenna:** DIY Yagi antenna to improve communication direction and gain, built with affordable materials.

### Energy Systems

- **Solar Panels:** **Polycrystalline Panels** - Economical and sufficient for power generation in small space projects.
- **Solar Charge Controller:** **PWM Controller** - Affordable solution for basic solar panel charge management.
- **Battery:** Car batteries or **refurbished 18650 batteries** - Inexpensive alternative for energy storage, using reused batteries from old laptops.

### Thermal Control

- **Heat Blankets:** **Mylar Blankets** - Inexpensive solution for thermal insulation, using lightweight and reflective materials.

### Propulsion System

- **Cold Gas Thrusters:** DIY thrusters using paintball CO2 bottles, release valves, for safe and economical maneuvers.

### Navigation and Control Systems

- **GPS:** **NEO-6M GPS Module** - Affordable GPS module, suitable for basic navigation and position tracking.

### Internet Communication

- **RF Transmitter (HackRF One or similar):** Transmits internet data using RF waves that can be received on Earth with proper antennas.
- **Antennas on Earth:** Users on Earth will require directional antennas to receive the RF signal, convert it to Wi-Fi using SDR technology.

## Safety System

- **Function:** Disables the fuel system and activates a giant parachute in case of failure or danger.
- **Mechanism:** Remotely activated to ensure safety in case of critical failure.

## Software

- **Development:** Using Ubuntu, Python, C, Assembly, and Java for managing sensors, RF communication, and control systems.
- **Communication Protocols:** The Raspberry Pi will use TCP/IP over RF to transmit internet data. It will modulate data into RF signals via the SDR system, using GNU Radio software for handling transmission protocols.

## Satellite Design

- **Structure:** Compact and lightweight, using steel and aluminum.
- **Solar Panels:** For power generation.
- **Battery:** Car battery or 18650 batteries for energy storage.

## Launch

- **Preparation:** Assembly at the launch site.
- **Fuel:** Gasoline or alternative propulsion system will be added at the launch site.
- **Safety Procedures:** Safe distance and remote activation of the security system.

### Launch Planning

- **Assembly Phase:** Assemble the satellite and add fuel at the launch site.
- **Remote Activation:** Remotely activated security system to cut off fuel and open the parachute in case of emergency.

## Repositories

### - **3D Model:** [GitHub - Vortex-01 Model](https://github.com/Vortex-01/Model)
### - **Source Code:** [GitHub - Vortex-01 Source Code](https://github.com/Vortex-01/Source-Code)

## Components for RF to Wi-Fi Conversion

### Satellite Side:
- **Raspberry Pi 4B**
- **HackRF One (or SDR Transmitter)**
- **Broadband Dipole/Yagi Antennas**
- **GNU Radio Software**

### Earth Side:
- **Yagi or Directional Antennas**
- **RTL-SDR or similar SDR Receiver**
- **Raspberry Pi (or Wi-Fi Router) for RF to Wi-Fi conversion**
