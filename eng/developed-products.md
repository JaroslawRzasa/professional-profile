# Developed Products

A curated overview of the products, tools, and functionalities I have designed and developed throughout my career. All of the work below was delivered as part of a team; the scope and nature of my individual contribution to each is described alongside the product.

## Puzzle Club

### Puzzle-Solving Software
Developed software for solving math and logic puzzles, implementing solving algorithms in Python, C#, and C++.


## Comernal Software

### Cyclone REGISTER 360 PLUS
Point-cloud registration and processing software for laser scan data, developed for client Leica Geosystems (part of Hexagon) and used to align scan setups, manage registration projects, and produce deliverables for surveying, construction, and BIM/AEC workflows. Main contribution: the new GeoTag system — particularly multi-asset GeoTags, which let a single tag carry several attached files, links, and multimedia items such as BIM deviation reports, maintenance schedules, or warranty information — plus ongoing bug fixing.

### Leica GR30 & GR50
GNSS reference servers, developed for the same client, supporting all major global GNSS constellations (GPS, GLONASS, Galileo, BeiDou) and regional augmentation systems, with NTRIP server/client/caster functionality. Main contribution: porting the receiver software from Windows CE to a Linux-based platform (Yocto Project), adding support for new GNSS signal types alongside their global rollout, implementing IPv6 networking, and ongoing bug fixing. Introduced automated functional testing for the product line (the first such framework on the team): built in Python with Selenium and ChromeDriver.

### Meet and Play
A self-initiated Android math/logic game (Nim) built after hours with three Comernal Software colleagues, run as an independent product-development effort. Designed the MVC split between the C# game engine and the Unity front end, combined the Product Owner and developer roles, and shipped the game to Google Play.


## Rockwell Automation

### NetLinx Protocol Stack Binarization
Refactored the firmware for Rockwell Automation's ControlLogix family of industrial programmable automation controllers (PLCs), implementing the NetLinx Unified Common Industrial Protocol and extracting a core communication-stack library fully independent from the rest of the firmware layers.


## Mentor Graphics

### Data Acquisition Unit
Developed for Valor, an Israeli company acquired by Mentor Graphics. A component of a SCADA solution that collects data from inputs and control outputs, translates it into Open Manufacturing Language (XML/JSON), and transports it over XMPP. Built on Intel Quark and ARM hardware running a customized Yocto Linux, with the application written in C++ and C across both userland and kernel space.

### Xpedition PCB
The remaining contributions were made to Xpedition PCB, Mentor Graphics' professional PCB design and layout software suite used by electronics engineers to design printed circuit boards and IC packaging. Built primarily in C++ with MFC and COM (plus OpenGL for 3D visualization), running on Windows, Linux, SunOS, and HP-UX (32/64-bit), with fully automated unit and functional testing throughout:

- **Display & component control** — a dynamically generated dialog for controlling more than a thousand item types, with per-item visibility, colour, and pattern settings, favourites, scheme save/load, search, and hide/show, complemented by a component explorer for managing board placement.
- **Wirebonding suite** — advanced IC-packaging functionality for designing and validating wire bonds: parametric wire modelling with rounded or Bézier-curve corners, 3D Design Rule Check for proximity-hazard detection (online and batch modes), automated wire-pattern generation with full 3D DRC validation, configurable multi-wire-bond rules, and die stacking/cavity support.
- **RF design** — stitch-via generation to minimize radiation loss (within planes, along contours, or in radial/array patterns) and entry rules controlling RF connection direction, manually or automatically.
- **Embedded passives** — design of embedded passive elements directly on the PCB.


## Proventus sp. z o.o.

### Crossover Management Application
Additional B2B contract engagement: a Windows desktop application for auditing telecom crossovers, built in C++ with a local SQLite database. *(Engagement dates: NO DATA AVAILABLE — to be filled in; this engagement also has no separate entry in the [Career Timeline](work-history-brief.md).)*


## R&D Centre for Electrical Engineering and Automation in Mining EMAG

A series of embedded and desktop C/C++ applications supporting mine safety, monitoring, and industrial communication:

- **Connections Identification Console** — monitors telephone calls, detects DTMF signals, and maintains a connection journal via a serial-connected listening device.
- **LED Table Control Server** — drives the control-room LED board and maps LEDs to sensors.
- **MODBUS Communication Server** — a unified library for communication over the Modbus protocol.
- **People Movement Monitoring System** — tracks miners' locations by region, with a monitoring application and event journal.
- **Intrinsically-Safe Telecommunications Meter MIT** — a device for auditing electrical lines in mines; covered mechanical design, PCB design, and firmware/PC application development.
- **Data Transmission Library** — a unified communication library supporting configuration of multiple serial communication channels.
- **Data Distribution Server** — a publisher-subscriber server running on Linux.
