# VIRUS2 instrument at HJST

Control software and documentation developed for the VIRUS2 spectrograph at HJST.

## VIRUS2 Overview

The VIRUS2 Instrument is an [integral field spectrograph](https://en.wikipedia.org/wiki/Integral_field_spectrograph) for the [2.7m Harlan J. Smith Telescope](https://mcdonald.utexas.edu/research-facilities/HJST) at the [McDonald Observatory](https://mcdonald.utexas.edu).
- [SPIE, Volume 10702, id. 107028E 9 pp. (2018).](https://ui.adsabs.harvard.edu/abs/2018SPIE10702E..8EL/abstract)
- [VIRUS2 References and Publications](https://github.com/mcdo-hjst/virus2-docs/virus2-references.md)

VIRUS2 was preceded by several other related instruments:
- [VIRUS-W at HJST](https://mcdonald.utexas.edu/research-facilities/HJST/VIRUS-W)
- [GCMS at HJST](https://mcdonald.utexas.edu/research-facilities/HJST/gcms)
- [VIRUS at HET](https://hydra.as.utexas.edu/?a=help&h=108)

## VIRUS2 Repositories

Some repositories are currently private and will return a `404` if you are not a member of the development team.

- VIRUS2 Systems
    - **[virus2-systems](https://github.com/mcdo-hjst/virus2-systems/)**: Host system OS install, networking configuration, and user accounts
- VIRUS2 Detector and Cryostat
    - **[virus2-archon](https://github.com/mcdo-hjst/virus2-archon/)**: CCD detector control software
    - **[virus2-cryocooler](https://github.com/mcdo-hjst/virus2-cryocooler/)**: Cryo-cooler control software
    - **[virus2-enclosure](https://github.com/mcdo-hjst/virus2-enclosure/)**: Unit enclosure sensor software
    - **[virus2-pump](https://github.com/mcdo-hjst/virus2-pump/)**: Ion pump control software
- VIRUS2 Input Head
    - **[virus2-actuator](https://github.com/mcdo-hjst/virus2-actuator/)**: Focal stage position actuator control software
    - **[virus2-calibration](https://github.com/mcdo-hjst/virus2-calibration)**: Input head assembly and calibration control software
    - **[virus2-camera](https://github.com/mcdo-hjst/virus2-camera/)**: Focus and guide camera interface software
    - **[virus2-focus](https://github.com/mcdo-hjst/virus2-focus/)**: Focus camera stage controls and focal metrics
- VIRUS2 Telescope Interface
    - **[virus2-guider](https://github.com/mcdo-hjst/virus2-guider/)**: Guider and interface for HJST telescope control system
    - **[virus2-tcs](https://github.com/mcdo-hjst/virus2-tcs/)**: control interface for HJST TCS (via TCSMON)
- WIP: VIRUS2 Applications Framework, Systems Integration, and User Interfaces 
    - **[virus2-framework](https://github.com/mcdo-hjst/virus2-framework/)**: RPC and Messaging Application framework for systems integration, controls, and messaging
    - **[virus2-unit](https://github.com/mcdo-hjst/virus2-unit/)**: Unit RPC and Messaging server/client applications
    - **[virus2-dashboards](https://github.com/mcdo-hjst/virus2-dashboards/)**: science user interface dashboards for monitoring and control

