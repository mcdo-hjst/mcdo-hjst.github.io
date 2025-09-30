# TCS at HJST

Documentation and software for the telescope control systems at HJST

## TCS Overview

- TCS is the "Telescope Control System" which controls the positioning of the [2.7m Harlan J. Smith Telescope](https://mcdonald.utexas.edu/research-facilities/HJST) at the [McDonald Observatory](https://mcdonald.utexas.edu).
- TCS is composed of 3 main components:
    - PMAC: Programmable Multi-Axis Controller, a low-level motion control system of hardware and software: 
    - TCSMON: Telescope Control System Monitor Resource Serve, a mid-level motion control process, provides the motion control API for client software, received requests from TCS clients, talks to the PMAC.
    - TCS GUI: a graphical user interface application used by science observers, talks to TCSMON
- The control process can be communicated with via either the TCS GUI and a TCS CLI, both of which communicate via the `TCSMON` process.
- Many science users have historically referred to the `TCS GUI` application as "TCS", and/or conflated the GUI with the entire TCS system.

## TCS Legacy

- **[hjst-tcs-docs](https://github.com/mcdo-hjst/hjst-tcs-docs/)**: Documentation for TCS (1999-2025)
- **[hjst-tcs-tcsmon](https://github.com/mcdo-hjst/hjst-tcs-tcsmon/)**: Python CLI client for HJST TCS (developed 2024, also talks to TCSMON)

## TCS Upgrade

Starting in 2024, funds have been allocated and work begun on upgrades to the current telescope control systems at HJST

- **[hjst-tcs-analysis](https://github.com/mcdo-hjst/hjst-tcs-analysis)**: WIP: Engineering analysis and documentation of the telescope motion control system.
- **[hjst-tcs-pmac](https://github.com/mcdo-hjst/hjst-tcs-pmac)**: WIP: Software for HJST PMAC motion controller, including motional control (MC) language, programmable logic controller (PLC) language, and GPASCII (CLI)
- **[hjst-tcs-telescopy](https://github.com/mcdo-hjst/hjst-tcs-telescopy)**: WIP: Communications and command interface for new telescope motion controller under development.


