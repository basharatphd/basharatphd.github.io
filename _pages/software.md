---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Below you can find links to repositories for software, data and models that have been developed by my team in different projects:

# Almost Everything
  - [ALSETLab on Github!](https://github.com/ALSETLab): All code repositories related to Luigi's work, except OpenIPSL.

# Curated Software Project Lists


## Modeling and Simulation with Modelica

## OpenIPSL - Modelica for Power Grid Simulation using the Phasor Modeling Construct
### The Library:
  - [OpenIPSL](http://openipsl.org): The [OpenIPSL.org](http://openipsl.org) project with our Modelica library for power system simulation.

### Reproduce examples from our own research:
  - Example Models from Publications:
    - PMU-based control design for islanded frequency control, [here](https://github.com/ALSETLab/2018_AmericanModelicaConf_PMUBasedIslanding)
    - Multi-Domain power grid and gas turbine simulation, [here](https://github.com/ALSETLab/2018_AmericanModelicaConf_PowerGrid_plus_PowerSystems)
    - The Nordic 44 (or N44) test system has been modified for the analysis of large-scale hybrid model DAE models [here](https://github.com/ALSETLab/2019_Modelica_Conf_DAESolvers4LargeHybridModels)

## Modelica for Power Electronics:
  - An implementation of an Average-Valued Model of a VSC HVDC model in Modelica, compared 1-to-1 with [EMTP-RV](http://emtp.com) ('The reference for power system transients') can be found [here](https://github.com/ALSETLab/2017_ModelicaConf_VSC-HVDC_AVM_Model)

## Real-Time Simulation Models
  - An Active Distribution Network model for Opal-RT's and EMTP-RV (off-line) platforms can be found [here](https://github.com/ALSETLab/ADN-RT-EMTP-Model)
  - An IRIG-B Signal Generator for Real-Time Simulation can be found [here](https://github.com/ALSETLab/IRIG-B_for_RT)
  - More to come...

## Model Transformation Tools
  - [CIM2MOD(elica)](https://github.com/ALSETLab/cim2modelica) is a CIM-2-Modelica Model Transformation Tool

## System Identification Tools
### RaPId
  - [RaPId](https://github.com/ALSETLab/RaPId) RaPId (a recursive acronym for "Rapid Parameter Identification") utilizes different optimization and simulation technologies to provide a framework for model validation and calibration of any kind of dynamical systems, but specifically catered to power systems.

## Synchrophasor / PMU Tools and Apps

## User Tools:
- [S3DK](https://alsetlab.github.io/S3DK/): A library for PMU App. Development under LabVIEW
  - LabVIEW Library, [here](https://github.com/ALSETLab/S3DK)
  - LabVIEW Library Documentation, [here](https://alsetlab.github.io/S3DK/docs/S3DK_Utilities_VI_Overview.html)
  - Examples can be found with the library, with documentation [here](https://alsetlab.github.io/S3DK/docs/PDC_Reader.html)

- PUPo: A PMU / PDC Stream Emulator
  - Executable, [here](https://github.com/ALSETLab/PMU-PDC-StreamSimulator/releases)
  - Usage Documentation, [here](https://github.com/ALSETLab/PMU-PDC-StreamSimulator/blob/master/docs/Simulator_documentation.md)

- [Audur](https://github.com/ALSETLab/Audur): software for PMU-based control system implementation using the National Instruments cRIO hardware platform.
  - Software, [here](https://github.com/ALSETLab/Audur)
  - Documentation, [here](https://www.sciencedirect.com/science/article/pii/S2352711018301730?via%3Dihub)

- BabelFish Tools:
  - Overview and Documentation, [here](https://doi.org/10.1016/j.softx.2017.08.002)
  - LabVIEW only-implementation, [here](https://github.com/ALSETLab/BabelFish/releases/tag/v1.1.0)
  - LabVIEW with ActiveX Bindings to C++ DLL, [here](https://github.com/ALSETLab/BabelFish/tree/master/BabelFish%20V1)
  - Related Publication, [here](https://ieeexplore.ieee.org/document/7131910?arnumber=7131910)

## Apps based on the S3DK:
- Display/Visualization example project, [here](https://github.com/ALSETLab/S3DK-SynchrophasorDisplay).
- Mode Estimation example project, [here](https://github.com/ALSETLab/Ambient-Mode-Estimator):
  - Software project, [here](https://github.com/ALSETLab/Ambient-Mode-Estimator/releases/tag/v0.1-beta).
  - Documentation, [here](https://github.com/ALSETLab/Ambient-Mode-Estimator/blob/master/docs/Main_v1.1.md).
- ... more to come.

## Developer Tools:
- [STRONgrid](https://github.com/ALSETLab/S3DK-STRONGgrid): Real-time PMU data mediation library with several future functionalities in mind, such as a time-synchronization layer and multithreading - and LabView API.
  - An overview can be found [here](http://www.sciencedirect.com/science/article/pii/S2352711018301705)
  - Software release, [here](https://github.com/ALSETLab/S3DK-STRONGgrid/releases)
  - Online documentation for LabVIEW API, [here](https://alsetlab.github.io/S3DK/docs/STRONGgrid_DLL_Overview.html)
  - Build documentation, [here](https://alsetlab.github.io/S3DK/docs/Stronggrid.html)

## OpenPMU version 1 (legacy)
- Documentation on the LabVIEW Software, [here](https://alsetlab.github.io/S3DK/docs/Code_Flow_Chart.html)
- "Maker" Guide: coming soon.

# Legacy Projects:

### PST, PST Coherency Toolbox and MatNet Programs Distribution
- **Note**: Please DO NOT email me with questions regarding PST and other software, I do not longer provide support.
- Power System Toolbox (PST), PST Coherency Toolbox, MatNetFlow and MatNetEig:
  - To obtain the passwords to decompress the .zip files, file out the following form, the passwords are presented to you after you complete it: [click here](https://forms.gle/q4qrUYKMXUb7SiCS8)
  - To download the individual .zip files for the software, browse the directory and download the .zip files by [clicking here](https://ecse.rpi.edu/~vanfrl/documents/pst_etal/).


### While you are here, take the chance to ...
  - See how you can help! Click [here](https://alsetlab.github.io/donate/).
