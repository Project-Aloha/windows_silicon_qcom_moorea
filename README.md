# Windows on Snapdragon 730/730G/732G Board Support Package

Welcome to the Snapdragon 730/730G/732G Windows BSP Platform repository.

This repository contains drivers, components and files needed to run Windows on official Snapdragon 730/730G/732G platforms such as:

- QRD
- IDP

We currently support the following chipsets:

- Snapdragon 730
- Snapdragon 730G
- Snapdragon 732G

In the following variants:

- MSM
  
And with the following configurations:

- Standard (Built in Snapdragon X15 LTE Modem)
  
## Currently non functional chipset features

- A specific set of onboard TLMM Interrupts **over PDC**
- GPI on specific I2C Buses
- Battery Power Management Stack
- Audio DSP (50/50)
- DSP based NPU
- CPU Cores Frequency Management (for Snapdragon 730 and 730G)
- Hyper-V
- IOMMU Mappings for Hyper-V
- NFC
- PCIe
- PM7150B/L/A's PWM/LPG/RGB controllers (for LEDs)
- PM7150L/A PWM controller (for haptics)
- Proper Thermal and SoC bandwidth management between all components
- TPM
- Type-C role detection

## Relevant Documentation

You can find a few notes under the docs folder inside this repository.

## Stay in touch!

For specific Snapdragon 730/730G/732G BSP related inquiries, feel free to reach out on this github repository issue tracker, discussion board, or on telegram at:

- https://t.me/project_aloha_issues (if your question is not Surface Duo related, or concerns a specific third party OEM made phone, or is about the Snapdragon 730/730G/732G BSP in general)

(Wait for an answer as well, we are not always available for inquiries)

## Misc

These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

## Resources

## Copyright, License, Disclaimers and end user license agreement

**Below notice must be present in all redistributed portions of this software**

Please see [LICENSE](LICENSE.md)

## Installing manually

For preserving charset encoding, please checkout with using:

```
git clone -c core.autocrlf=false https://github.com/Project-Aloha/windows_silicon_qcom_moorea
```
