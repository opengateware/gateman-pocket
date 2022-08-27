# Gateman Pocket

Gateman Pocket is an Analogue Pocket gateware library that allows for Gateman-based projects to be built for the Pocket openFPGA Platform.
Gateman based applications are gateware IP (Intellectual Properties) Cores written with HDL technology: Verilog, SystemVerilog or VHDL (Very High-Speed Integrated Circuit Hardware Description Language)

## Requirements

- [Gateman CLI]
- [Intel Quartus Lite] 18.x or greater with device support for Cyclone V.
- [Analogue Pocket]
  - Dock and DAC are optional
- Intel Approved USB or Ethernet Blaster JTAG cable
  - Intel/Altera or [Terasic](https://www.digikey.com/en/products/detail/terasic-inc/P0302/2003484) versions of this tool are supported. Clone tools are not suggested and may have unexpected behavior and/or cause hardware damage.
- [Torx T-6](https://www.digikey.com/en/products/detail/wiha/36266/510975) screwdriver for removing the rear cover to access the JTAG header
  - Not required on Pocket Developer Edition, which have a removable door on the rear cover.
- Micro SD card
  - Up to 1TB
  - FAT32 or exFAT supported

### Optional

- Analogue Developer Key
  - For additional debugging features via the cartridge bus
- Docker
  - For headless compilation flow

## Create a Gateman project

Follow the instructions in the [Create your first gateware] section of [Gateman Documentation]

## Adding the platform to a project

When you install a platform, the [Gateman CLI] will pin the installed version to your `gateware.json` file. If no version is specified, the lastest version will be installed.

```bash
# Grab the latest version
gateman platform add pocket
# or specify a version of the platform
gateman platform add pocket@1.1.0
```

## Updating a project

Follow these simple upgrade steps within your project:

```bash
gateman platform rm pocket
gateman platform add pocket
```

## Further reading

- [OpenGateware]
- [Analogue openFPGA]
- [openFPGA SDK Documentation]

## Legal

Analogue’s Development program was created to further video game hardware preservation with FPGA technology.
Analogue Developers have access to Analogue Pocket I/O’s so Developers can utilize cartridge adapters or interface with other pieces of original or bespoke hardware to support legacy media.
Analogue does not support or endorse the unauthorized use or distribution of material protected by copyright or other intellectual property rights.

[Intel Quartus Lite]: https://www.intel.com/content/www/us/en/products/details/fpga/development-tools/quartus-prime/resource.html
[Analogue openFPGA]: https://www.analogue.co/developer
[openFPGA SDK Documentation]: https://www.analogue.co/developer/docs/overview
[Gateman CLI]: https://github.com/opengatware/gateman
[Create your first gateware]: https://opengatware.org/docs/cli/getting-started.html
[Gateman Documentation]: https://opengatware.org/docs
[Analogue Pocket]: https://www.analogue.co/pocket
[OpenGateware]: https://www.opengateware.org
