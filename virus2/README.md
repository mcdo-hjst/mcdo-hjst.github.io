# VIRUS2 Instrument at HJST

Control software and documentation developed for the VIRUS2 spectrograph at HJST.

## VIRUS2 Overview

- "VIRUS" = "Visible Integral-Field Replicable Unit Spectrograph"
- The VIRUS2 Instrument is an [integral field spectrograph](https://en.wikipedia.org/wiki/Integral_field_spectrograph) for the [2.7m Harlan J. Smith Telescope](https://mcdonald.utexas.edu/research-facilities/HJST) at the [McDonald Observatory](https://mcdonald.utexas.edu).
- Overview publications:
    - [ADS, NSF Proposal (2015)](https://ui.adsabs.harvard.edu/abs/2015nsf....1532169H/abstract) 
    - [ADS, SPIE, Volume 10702, id. 107028E 9 pp. (2018).](https://ui.adsabs.harvard.edu/abs/2018SPIE10702E..8EL/abstract)

## VIRUS2 Software Repositories

Some repositories are currently private and will return a `404` if you are not a member of the development team.

- VIRUS2 Systems
    - **[virus2-systems](https://github.com/mcdo-hjst/virus2-systems/)**: Host system OS install, networking configuration, and user accounts
- VIRUS2 Detector and Cryostat
    - **[virus2-archon](https://github.com/mcdo-hjst/virus2-archon/)**: CCD detector control software
    - **[virus2-chiller](https://github.com/mcdo-hjst/virus2-chiller/)**: Glycol coolant chiller control software
    - **[virus2-collimator](https://github.com/mcdo-hjst/virus2-collimator/)**: Collimator mirror positioning control
    - **[virus2-cryocooler](https://github.com/mcdo-hjst/virus2-cryocooler/)**: Cryo-cooler control software
    - **[virus2-enclosure](https://github.com/mcdo-hjst/virus2-enclosure/)**: Detector unit enclosure software
    - **[virus2-pump](https://github.com/mcdo-hjst/virus2-pump/)**: Ion pump control software
    - **[mcdo-calibration](https://github.com/mcdo-hjst/mcdo-calibration/)**: Lab calibration unit control software
- VIRUS2 Input Head
    - **[virus2-actuator](https://github.com/mcdo-hjst/virus2-actuator/)**: Focal stage position actuator control software
    - **[virus2-calibration](https://github.com/mcdo-hjst/virus2-calibration)**: Input head assembly and calibration control software
    - **[virus2-camera](https://github.com/mcdo-hjst/virus2-camera/)**: Focus and guide camera interface software
    - **[virus2-focus](https://github.com/mcdo-hjst/virus2-focus/)**: Focus camera stage controls and focal metrics
- VIRUS2 Telescope Interface
    - **[virus2-guider](https://github.com/mcdo-hjst/virus2-guider/)**: Guider and interface for HJST telescope control system
- VIRUS2 Systems Integration
    - **[virus2-framework](https://github.com/mcdo-hjst/virus2-framework/)**: RPC and Messaging Application framework for systems integration, controls, and messaging
    - **[virus2-unit](https://github.com/mcdo-hjst/virus2-unit/)**: Unit RPC and Messaging server/client applications
    - **[virus2-dashboards](https://github.com/mcdo-hjst/virus2-dashboards/)**: science user interface dashboards for monitoring and control
- Data Reduction
    - [VIRUS Data Reduction with Antigen](https://github.com/maya-debski/Antigen)
    - [Data Pipelines for HJST instruments](https://mcdonald.utexas.edu/observing/pipelines)

## VIRUS Instrument History

VIRUS2 was preceded by several other integral field spectrograph instruments at MCDO:
- (1) [GCMS at HJST](https://mcdonald.utexas.edu/research-facilities/HJST/gcms)
    - Initially know as "VIRUS-P" or "VIRUS Prototype" 
    - [GCMS instrument details](https://mcdonaldobservatory.org/research/instruments/mitchell-spectrograph)
- (2) [VIRUS at HET](https://hydra.as.utexas.edu/?a=help&h=108)
   - https://arxiv.org/abs/2110.03843
   - https://hetdex.org/about-hetdex/
   - https://hetdex.org/papers/
- (3) [VIRUS-W at HJST](https://mcdonald.utexas.edu/research-facilities/HJST/VIRUS-W)
    - [VIRUS-W: an integral field unit spectrograph dedicated to
the study of spiral galaxy bulges](https://mcdonald.utexas.edu/media/98/download?inline) 
    - [VIRUS-W: Commissioning and First-Year Results](https://mcdonald.utexas.edu/media/272/download?inline)

## VIRUS2 Publications

- Links to SPIE (Society of Photo Instrument Engineers) conference proceedings papers published for the VIRUS2 project. 
- While on the UT Austin VPN, one should be able to access and download the paper PDFs.
  - https://doi.org/10.1117/12.2314128
  - https://doi.org/10.1117/12.2562623
  - https://doi.org/10.1117/12.2562804
  - https://doi.org/10.1117/12.2562834
  - https://doi.org/10.1117/12.2563202
  - https://doi.org/10.1117/12.2563119
  - https://doi.org/10.1117/12.2627345
  - https://doi.org/10.1117/12.2628838
  - https://doi.org/10.1117/12.2629320
  - https://doi.org/10.1117/12.2629933
