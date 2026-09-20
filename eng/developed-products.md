# Developed Products

A curated overview of the products, tools, and functionalities I have designed and developed throughout my career. All of the work below was delivered as part of a team, though my role was significant — often the leading one — on most of these projects.

## Puzzle Club

### Puzzle-Solving Software
Developed software for solving math and logic puzzles, implementing solving algorithms in Python, C#, and C++.


## Rockwell Automation

### NetLinx Protocol Stack Binarization
Refactored the firmware for the ControlLogix device family, implementing the NetLinx Unified Common Industrial Protocol and extracting a core communication-stack library fully independent from the rest of the firmware layers.


## Mentor Graphics

### Data Acquisition Unit
A component of a SCADA solution that collects data from inputs and control outputs, translates it into Open Manufacturing Language (XML/JSON), and transports it over XMPP. Built on Intel Quark and ARM hardware running a customized Yocto Linux, with the application written in C++ and C across both userland and kernel space.

### Xpedition PCB – Display & Component Control
A dynamically generated dialog for controlling more than a thousand item types in Xpedition PCB, with per-item visibility, colour, and pattern settings, plus favourites, scheme save/load, search, and hide/show. Complemented by a component explorer for managing component placement on the board. Built with C++, MFC, and COM for Windows and Linux (32/64-bit); testing was fully automated.
Demo: https://www.youtube.com/watch?v=tRvLLJtTwW4&feature=youtu.be

### Xpedition PCB – Wirebonding Suite
Advanced packaging functionality for designing and validating wire bonds in IC packaging:
- Parametric wire modelling, with rounded or Bézier-curve corners
- 3D Design Rule Check (DRC) for proximity-hazard detection, in both online and batch modes
- Automated wire-pattern generation with full 3D DRC validation
- Configurable rules and parameters for multi-wire-bond connections
- Die stacking and cavity support

Built with C++, MFC, COM, and OpenGL, for Windows, Linux, SunOS, and HP-UX (32/64-bit); fully automated unit and functional testing.
Demo: https://youtu.be/xMeAEk12Yfw

### Xpedition PCB – RF Design
Functionality for designing radio-frequency elements on the PCB:
- Stitch-via generation to minimize radiation loss, placed within planes, along contours, or in radial/array patterns
- Entry rules controlling RF connection direction, manually or automatically

Built with C++, MFC, and COM, for Windows, Linux, SunOS, and HP-UX (32/64-bit); fully automated unit and functional testing.
Demo: https://youtu.be/qaeOii1rLN0

### Xpedition PCB – Embedded Passives
Functionality for designing embedded passive elements directly on the PCB. Built with C++, MFC, and COM, for Windows, Linux, SunOS, and HP-UX (32/64-bit); fully automated unit and functional testing.


## Proventus sp. z o.o. *(additional B2B contract engagement)*

### Crossover Management Application
A Windows desktop application for auditing telecom crossovers, built in C++ with a local SQLite database.


## R&D Centre for Electrical Engineering and Automation in Mining EMAG

A series of embedded and desktop C/C++ applications supporting mine safety, monitoring, and industrial communication:

- **Connections Identification Console** — monitors telephone calls, detects DTMF signals, and maintains a connection journal via a serial-connected listening device.
- **LED Table Control Server** — drives the control-room LED board and maps LEDs to sensors.
- **MODBUS Communication Server** — a unified library for communication over the Modbus protocol.
- **People Movement Monitoring System** — tracks miners' locations by region, with a monitoring application and event journal.
- **Intrinsically-Safe Telecommunications Meter MIT** — a device for auditing electrical lines in mines; covered mechanical design, PCB design, and firmware/PC application development.
- **Data Transmission Library** — a unified communication library supporting configuration of multiple serial communication channels.
- **Data Distribution Server** — a publisher-subscriber server running on Linux.
