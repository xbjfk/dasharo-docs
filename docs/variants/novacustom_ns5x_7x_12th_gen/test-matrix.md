# Test matrix

## About

The test matrix is used to determine the scope of tests to which the DUT is
subjected before the release of the new binary.

## Module: Dasharo compatibility

| No.  | Supported test suite                                   | Test suite ID | Supported test cases                 |
|:----:|:-------------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [Memory HCL][HCL]                                      | HCL           | All                                  |
| 2.   | [UEFI compatible interface][EFI]                       | EFI           | All                                  |
| 3.   | [Display ports and LCD support][DSP]                   | DSP           | DSP001.001, DSP001.002, DSP001.003, DSP002.001, DSP002.002, DSP002.003 |
| 4.   | [Embedded Controller and Super I/O initialization][ECR]| ECR           | Without ECR010.001 and ECR010.002   |
| 5.   | [NVMe support][NVM]                                    | NVM           | All                                  |
| 6.   | [Custom logo][CLG]                                     | CLG           | All                                  |
| 7.   | [Custom boot keys][CBK]                                | CBK           | All                                  |
| 8.   | [USB HID and MSC Support][USB]                         | USB           | All                                  |
| 9.   | [Debian Stable and Ubuntu LTS support][LBT]            | LBT           | All                                  |
| 10.  | [UEFI Shell][USH]                                      | USH           | All                                  |
| 11.  | [Windows booting][WBT]                                 | WBT           | WBT001.001                           |
| 12.  | [Audio subsystem][AUD]                                 | AUD           | All                                  |
| 13.  | [USB-C/Thunderbolt][UTC]                               | UTC           | All                                  |
| 14.  | [Network boot][PXE]                                    | PXE           | Without PXE007.001                   |
| 15.  | [M.2 WiFi/Bluetooth][WLE]                              | WLE           | All                                  |
| 16.  | [SD card support][SDC]                                 | SDC           | All                                  |
| 17.  | [USB Camera verification][CAM]                         | CAM           | All                                  |
| 18.  | [Custom fan curve][FAN]                                | FAN           | FAN001.001                           |
| 19.  | [SMBIOS][DMI]                                          | DMI           | All                                  |
| 20.  | [Docking station detect][DUD]                          | DUD           | All                                  |
| 21.  | [Docking station USB devices][DUB]                     | DUB           | All                                  |
| 22.  | [Docking station Audio][DAU]                           | DAU           | All                                  |
| 23.  | [Docking station USB-C][DUC]                           | DUC           | All                                  |
| 24.  | [Firmware update using fwupd][FFW]                     | FFW           | All                                  |
| 25.  | [Dasharo Tools Suite][DTS]                             | DTS           | DTS006.001, DTS007.001               |
| 26.  | [CPU status][CPU]                                      | CPU           | All                                  |
| 27.  | [Embedded controller flashing][ECF]                    | ECF           | All                                  |
| 28.  | [Logo customization functionality][LCM]                | LCM           | All                                  |
| 29.  | [Firmware locally building and flashing][FLB]          | FLB           | All                                  |

[HCL]: ../../unified-test-documentation/dasharo-compatibility/301-memory-hcl.md
[EFI]: ../../unified-test-documentation/dasharo-compatibility/30M-uefi-compatible-interface.md
[DSP]: ../../unified-test-documentation/dasharo-compatibility/31E-display-ports-and-lcd.md
[ECR]: ../../unified-test-documentation/dasharo-compatibility/31G-ec-and-superio.md
[NVM]: ../../unified-test-documentation/dasharo-compatibility/312-nvme-support.md
[CLG]: ../../unified-test-documentation/dasharo-compatibility/304-custom-logo.md
[CBK]: ../../unified-test-documentation/dasharo-compatibility/303-custom-boot-menu-key.md
[USB]: ../../unified-test-documentation/dasharo-compatibility/306-usb-hid-and-msc-support.md
[LBT]: ../../unified-test-documentation/dasharo-compatibility/308-debian-stable-and-ubuntu-lts-support.md
[USH]: ../../unified-test-documentation/dasharo-compatibility/30P-uefi-shell.md
[WBT]: ../../unified-test-documentation/dasharo-compatibility/31A-windows-booting.md
[AUD]: ../../unified-test-documentation/dasharo-compatibility/31F-audio-subsystem.md
[UTC]: ../../unified-test-documentation/dasharo-compatibility/31H-usb-type-c.md
[WLE]: ../../unified-test-documentation/dasharo-compatibility/318-m2-wifi-bluetooth.md
[SDC]: ../../unified-test-documentation/dasharo-compatibility/316-sdcard-reader.md
[CAM]: ../../unified-test-documentation/dasharo-compatibility/317-usb-camera.md
[FAN]: ../../unified-test-documentation/dasharo-compatibility/S30-fan-control.md
[DMI]: ../../unified-test-documentation/dasharo-compatibility/31L-smbios.md
[DUD]: ../../unified-test-documentation/dasharo-compatibility/323-docking-station-detect.md
[DUB]: ../../unified-test-documentation/dasharo-compatibility/324-docking-station-usb-devices.md
[DAU]: ../../unified-test-documentation/dasharo-compatibility/322-docking-station-audio.md
[DUC]: ../../unified-test-documentation/dasharo-compatibility/321-docking-station-usb-c.md
[FFW]: ../../unified-test-documentation/dasharo-compatibility/320-fwupd-firmware-update.md
[DTS]: ../../unified-test-documentation/dasharo-compatibility/326-dasharo-tools-suite.md
[ECF]: ../../unified-test-documentation/dasharo-compatibility/327-embedded_controller_flashing.md
[PXE]: ../../unified-test-documentation/dasharo-compatibility/315-network-boot.md
[CPU]: ../../unified-test-documentation/dasharo-compatibility/31T-cpu-status.md
[FLB]: ../../unified-test-documentation/dasharo-compatibility/326b-firmware-building-locally.md
[LCM]: ../../unified-test-documentation/dasharo-compatibility/328-logo-customization-functionality.md

## Module: Dasharo security

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:-----|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [TPM Support][TPM]                                | TPM           | All                                  |
| 2.   | [Verified Boot support][VBO]                      | VBO           | Without VBO006.001 and VBO007.001    |
| 3.   | [Measured Boot support][MBO]                      | MBO           | All                                  |
| 4.   | [Secure Boot support][SBO]                        | SBO           | All                                  |
| 5.   | [BIOS lock support][BLS]                          | BLS           | All                                  |

[TPM]: ../../unified-test-documentation/dasharo-security/200-tpm-support.md
[VBO]: ../../unified-test-documentation/dasharo-security/201-verified-boot.md
[MBO]: ../../unified-test-documentation/dasharo-security/203-measured-boot.md
[SBO]: ../../unified-test-documentation/dasharo-security/206-secure-boot.md
[BLS]: ../../unified-test-documentation/dasharo-security/20J-bios-lock-support.md

## Module: Dasharo performance

| No.  | Supported test suite                              | Test suite ID | Supported test cases                 |
|:-----|:--------------------------------------------------|:-------------:|:-------------------------------------|
| 1.   | [coreboot boot measure][CBMEM]                    | CBMEM         | All                                  |
| 2.   | [CPU temperature measure][CPT]                    | CPT           | All                                  |
| 3.   | [CPU frequency measure][CPF]                      | CPF           | All                                  |

[CBMEM]: ../../unified-test-documentation/dasharo-performance/400-coreboot-boot-measure.md
[CPT]: ../../unified-test-documentation/dasharo-performance/401-cpu-temperature.md
[CPF]: ../../unified-test-documentation/dasharo-performance/402-cpu-frequency.md