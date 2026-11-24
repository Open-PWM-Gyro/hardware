# Open-PWM-Gyro Hardware

This repository is a collection of hardware designs (KiCad projects) that can be used with the Open-PWM-Gyro firmware and software.

Each design lives in its own folder, and each folder name matches the board target name used in the firmware repository.

- Firmware: https://github.com/Open-PWM-Gyro/firmware
- Config app: **WIP**

## Designs

| Folder | Description | Status |
| --- | --- | --- |
| [`xiao-stm32c5/`](xiao-stm32c5/) | Seeed Studio XIAO STM32C5 module on a simple carrier board, designed to be easy to build by hand | Released |
| [`custom-stm32c5/`](custom-stm32c5/) | Fully custom board built around an STM32C5 | Planned |
| [`legacy/custom-stm32g4/`](legacy/custom-stm32g4/) | Original custom board built around an STM32G4 | Retired |

## Retired: custom-stm32g4

The STM32G431 design has been retired and is kept only for reference. It is not recommended for new builds, for two reasons:

- The STM32G431 has become much more expensive than the STM32C5.
- The status LED draws the absolute maximum rated current of an MCU IO pin.

The STM32C5 designs above replace it.
