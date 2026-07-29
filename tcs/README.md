# TCS at HJST

Documentation and software for the telescope control systems at HJST

## TCS Overview

- TCS is the "Telescope Control System" which controls the positioning of the [2.7m Harlan J. Smith Telescope](https://mcdonald.utexas.edu/research-facilities/HJST) at the [McDonald Observatory](https://mcdonald.utexas.edu).
- TCS is composed of 3 main components:
    - PMAC: Programmable Multi-Axis Controller, a low-level motion control system of hardware and software: 
    - TCSMON: Telescope Control System Monitor Resource Serve, a mid-level motion control process, provides the motion control API for client software, received requests from TCS clients, talks to the PMAC.
    - TCS Clients: e.g. TCS GUI application used by science observers, talks to TCSMON, and `pytcsmon` is a recently developed python client for TCSMON
- The control process can be communicated with via either the TCS GUI and a TCS CLI, both of which communicate via the `TCSMON` process.
- Many science users have historically referred to the `TCS GUI` application as "TCS", and/or conflated the GUI with the entire TCS system.

## TCS Upgrade

Starting in 2024, funds have been allocated and work begun on upgrades to the current telescope control systems at HJST

- **[hjst-tcs-gui](https://github.com/mcdo-hjst/hjst-tcs-gui)**: Python Tkinter GUI and PMAC simulator for the new TCS PMAC.
- **[hjst-tcs-pmac](https://github.com/mcdo-hjst/hjst-tcs-pmac)**: The new HJST PMAC motion control software, including motional control (MC) language, programmable logic controller (PLC) language, and GPASCII (CLI)
- **[hjst-tcs-tcsmon](https://github.com/mcdo-hjst/hjst-tcs-tcsmon/)**: Legacy TCS Monitor server source files and docs, and new python client for Legacy TCSMON process command interface
- **[hjst-tcs-telescopy](https://github.com/mcdo-hjst/hjst-tcs-telescopy)**: Communications and command interface for new telescope motion controller under development.

## Related resources

- [82in OttoStruve HOWTO Videos](https://www.youtube.com/playlist?list=PLoasOmkYn4S5n-wVjgpcYCFVMPcKBFUeU)
