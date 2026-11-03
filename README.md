# UM324xF SDK

UM324xF vendor libraries used by the Betaflight UM32 platform port.

## Contents

- `Drivers/CMSIS`: Arm CMSIS headers and UM324xF device support.
- `Drivers/UM324xx_HAL_Driver`: UM324xF HAL and low-level drivers.
- `Middlewares/UM/CherryUSB-1.6.0`: CherryUSB and the UM324xF USB port.
- `Middlewares/UM/ExtFunc_Library`: vendor extension library.

## Provenance

Imported without changes from `lib/main/UM324xx` in
[`unicmicro/betaflight-2026` at `31e5bcd3c023355d03a0195146e87eef09ded584`](https://github.com/unicmicro/betaflight-2026/tree/31e5bcd3c023355d03a0195146e87eef09ded584/lib/main/UM324xx),
the source revision of [Betaflight PR #15500](https://github.com/betaflight/betaflight/pull/15500).

The Betaflight platform integration is maintained in the firmware repository;
this repository contains the SDK payload only.

## Licensing

Original copyright and license notices are preserved in the files. CMSIS and
CherryUSB files identify their licenses in their headers. Unicmicro vendor
files retain their original notices. This import does not assign a new blanket
license to the SDK or change the licenses of bundled components.
