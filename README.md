# AlphaX FSAE ECU - Polytechnic University of Puerto Rico (Car #36)

This repository contains the EasyEDA schematic and PCB design files for an FSAE ECU used in 2026. This design successfully completed the endurance event in the Polytechnic University of Puerto Rico's car (number 36).

## Project Overview

- **Vehicle:** PUPR FSAE Car #36 (2026)
- **Status:** Race-proven (Completed 2026 Endurance)
- **Firmware Compatibility:** Designed for [rusEFI](https://rusefi.com/) firmware. AlphaX is a proud contributor to the rusEFI project.
- **Hardware Requirement:** This ECU is designed to be used with the [AlphaX Brainboard (STM32F407 rusEFI daughterboard)](https://alphaxpr.com/products/alphaecu-brainboard-stm32f407-rusefi-daughterboard) or a compatible equivalent.

## Hardware Specifications

- **Injector Drivers:** 4 channels available at the main connector.
- **Ignition Drivers:**
  - 2 channels available at the main connector.
  - 2 additional channels available via through-hole pads on the PCB.
- **Electronic Throttle Body (ETB) Support:** While the hardware supports ETB, it is important to note that the test car (PUPR #36) was **not** using ETB during the 2026 season.

## Support & Consulting

While this project is open-source, dedicated engineering support and consulting for integration, tuning, or hardware modifications are **billable**. 

- **Rate:** $150/hr (Suggested professional rate, adjustable based on scope).
- **Payment:** We accept direct payment or sponsorship credits.
- If your team or company requires professional assistance, please contact AlphaX for a formal quote.

## How to Open in EasyEDA

The project files are provided in `.json` format, which is native to EasyEDA (Standard Edition).

1. Go to [EasyEDA](https://easyeda.com/) and open the editor.
2. To open the Schematic:
   - Go to `File` -> `Open` -> `EasyEDA...`
   - Select `SCH_FSAE_PUPR_EVA34_2026-05-27.json` from your local machine.
3. To open the PCB:
   - Go to `File` -> `Open` -> `EasyEDA...`
   - Select `PCB_PCB_FSAE_PUPR_EVA34_2026-05-27.json` from your local machine.

## License

This project is licensed under the **GNU General Public License v3.0 (GPLv3)**. See the [LICENSE](LICENSE) file for details.
