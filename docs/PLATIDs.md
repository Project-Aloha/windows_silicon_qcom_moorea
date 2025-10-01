# ACPI Platform Identifiers

## Snapdragon 730/730G/732G

### ATP

| ACPI _SUB String (Subsystem/Platform ID) | Matching SOID (SoC ID) | Matching PLST (Platform Subtype) | Friendly Name      |
|------------------------------------------|------------------------|----------------------------------|--------------------|

### IDP

| ACPI _SUB String (Subsystem/Platform ID) | Matching SOID (SoC ID) | Matching PLST (Platform Subtype) | Friendly Name      |
|------------------------------------------|------------------------|----------------------------------|--------------------|
| IDP07150                                 | 365                    | 0                                | MSM™               |
| IDPA7150                                 | 366                    | 0                                | APQ™               |

### RUMI

| ACPI _SUB String (Subsystem/Platform ID) | Matching SOID (SoC ID) | Matching PLST (Platform Subtype) | Friendly Name      |
|------------------------------------------|------------------------|----------------------------------|--------------------|

### QRD

| ACPI _SUB String (Subsystem/Platform ID) | Matching SOID (SoC ID) | Matching PLST (Platform Subtype) | Friendly Name      |
|------------------------------------------|------------------------|----------------------------------|--------------------|
| QRD07150                                 | 365                    | 0                                | MSM™               |
| QRDA7150                                 | 366                    | 0                                | APQ™               |

# Device Tree Platform Identifiers

## Snapdragon 730/730G/732G

### ATP

| Device Tree Source File Name           | Matching ACPI Condition (Against header values prefilled from SMEM) |
|----------------------------------------|---------------------------------------------------------------------|

### IDP

| Device Tree Source File Name           | Matching ACPI Condition (Against header values prefilled from SMEM) |
|----------------------------------------|---------------------------------------------------------------------|
sdmmagpie-idp-overlay.dts                | Lequal(\\\_SB_.PSUB, "IDP07150") && Lequal(\\\_SB_.PLST, 0)         |
sdmmagpie-idp.dts                        | Lequal(\\\_SB_.PSUB, "IDP07150") && Lequal(\\\_SB_.PLST, 0)         |
sdmmagpiep-idp-overlay.dts               | Lequal(\\\_SB_.PSUB, "IDPA7150") && Lequal(\\\_SB_.PLST, 0)         |
sdmmagpiep-idp.dts                       | Lequal(\\\_SB_.PSUB, "IDPA7150") && Lequal(\\\_SB_.PLST, 0)         |

### RUMI

| Device Tree Source File Name           | Matching ACPI Condition (Against header values prefilled from SMEM) |
|----------------------------------------|---------------------------------------------------------------------|

### QRD

| Device Tree Source File Name           | Matching ACPI Condition (Against header values prefilled from SMEM) |
|----------------------------------------|---------------------------------------------------------------------|
sdmmagpie-qrd-overlay.dts                | Lequal(\\\_SB_.PSUB, "QRD07150") && Lequal(\\\_SB_.PLST, 0)         |
sdmmagpie-qrd.dts                        | Lequal(\\\_SB_.PSUB, "QRD07150") && Lequal(\\\_SB_.PLST, 0)         |
sdmmagpiep-qrd-overlay.dts               | Lequal(\\\_SB_.PSUB, "QRDA7150") && Lequal(\\\_SB_.PLST, 0)         |
sdmmagpiep-qrd.dts                       | Lequal(\\\_SB_.PSUB, "QRDA7150") && Lequal(\\\_SB_.PLST, 0)         |

---

_**© 2023-2025 Project Aloha**_

_Snapdragon is a registered trademark of Qualcomm Incorporated. Microsoft, the Microsoft Corporate Logo, Windows, Surface, Surface Duo, Windows Hello, Continuum, Hyper-V, and DirectX are registered trademarks of Microsoft Corporation in the United States. Android is a registered trademark of Google LLC. Miracast is a registered trademark of the Wi-Fi Alliance. Other binaries may be copyright Qualcomm Incorporated and Microsoft Surface._

_**Limited emergency calling**_

_Running Windows on your phone is not a replacement for a proper phone operating system and does not have emergency calling capabilities._

_**Hello from Seattle (US), France, Italy.**_