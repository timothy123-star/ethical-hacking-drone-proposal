# Ethical Hacking Drone – Project Proposal

**Author:** Okolo Timothy  
**Purpose:** Industrial Training Project at Terra Industries

## Overview
A drone equipped with a lightweight Wi-Fi adapter and onboard computer (e.g., Raspberry Pi) that can:
- Fly programmed missions
- Detect nearby Wi-Fi networks
- Perform automated penetration tests (deauthentication attack simulation, evil twin detection)
- Report vulnerabilities with GPS coordinates

## Why This Project
Current drones focus on surveillance or delivery. An ethical hacking drone allows companies to test their wireless security from the air – a growing need in industrial security.

## Technical Architecture (Planned)

### Hardware (to be provided by Terra Industries or simulated initially)
- Drone frame with flight controller (e.g., Pixhawk)
- Onboard computer: Raspberry Pi 4 or similar
- Wi-Fi adapter with monitor mode support (e.g., Alfa AWUS036ACH)
- Telemetry radio (3DR or similar)

### Software Stack
- **Flight Control:** ArduPilot / PX4 with MAVLink
- **Onboard Pen-Testing Scripts:** Python using `scapy` and `aircrack-ng` suite
- **Ground Control Station:** Node.js/Express backend + React frontend (my existing skill set)
- **Encrypted Telemetry:** AES-256 for command link
- **Reporting Engine:** JSON output with geolocated vulnerabilities

## What I Will Learn / Build During Internship
- Integrate cybersecurity tools with a real drone flight controller
- Implement secure command and control (C2) for the drone
- Test and log wireless vulnerabilities in controlled environments
- Deliver a working prototype and final report for my university

## Current Status
This is a detailed design proposal. I am ready to begin implementation immediately upon acceptance into the internship, using Terra Industries’ hardware and guidance.

## My Relevant Skills
- Backend development (Node.js, Python, C++)
- Cisco Ethical Hacking course (in progress)
- Hardware understanding (studied "Code: The Hidden Language of Computer Hardware and Software")
- Linux (HCIA openEuler – started)
