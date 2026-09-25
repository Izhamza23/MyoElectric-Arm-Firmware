# MyoElectric-Arm-Firmware
This repository regards all firmware advancements regarding the myoelectric arm project, including a demo of the arm and actuation of the project, launching it from a prototype vibe project to a real, applicable project.

## Repository structure

- `dsp/` — Portable C signal-processing library (no hardware dependencies)
- `tests/` — Unit tests run on a host machine
- `tools/` — Python scripts for loading datasets, plotting, and generating reference outputs
- `firmware/` — Microcontroller firmware (planned)

## Status

- [ ] Dataset exploration and signal analysis
- [ ] Python reference implementation of the pipeline
- [ ] C implementation of the DSP library
- [ ] Unit tests comparing C output to the Python reference
- [ ] Continuous integration
- [ ] RTOS firmware with DMA-based ADC sampling
- [ ] BLE streaming to a host app
- [ ] Integration with the physical arm

## Background

The original prototype used surface electrodes, an AD8221 instrumentation amplifier, an Arduino, and servo motors to control grip from forearm muscle signals. With this continuation I hope to create a more refined demo of the arm project shifting from prototype to applicable work.
