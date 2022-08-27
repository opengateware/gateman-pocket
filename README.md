# Gateman Pocket

Gateman Pocket is an Analogue Pocket gateware library that allows for Gateman-based projects to be built for the Pocket openFPGA Platform.
Gateman based applications are, at the core, applications written with HDL technology: Verilog, SystemVerilog and VHDL (Very High-Speed Integrated Circuit Hardware Description Language)

## Requirements

- Quartus 18.x or greater. Download it at the [Intel FPGA Software Download Center](https://www.intel.com/content/www/us/en/collections/products/fpga/software/downloads.html).
- [Gateman](#gateman)

## Create a Gateman project

Follow the instructions in the [Create your first gateware](#docs) section of [OpenGateware Gateman Docs](#docs)

## Updating a Gateman project

When you install a version of a platform, the [Gateman CLI](#) pins that version of specific platform, you can follow these simple upgrade steps within your project:

```bash
gateman platform rm pocket
gateman platform add pocket
```

## Further reading

- [Analogue openFPGA](www.analogue.co/developer)
- [openFPGA SDK Documentation](https://www.analogue.co/developer/docs/overview)

## Legal

Analogue’s Development program was created to further video game hardware preservation with FPGA technology.
Analogue Developers have access to Analogue Pocket I/O’s so Developers can utilize cartridge adapters or interface with other pieces of original or bespoke hardware to support legacy media.
Analogue does not support or endorse the unauthorized use or distribution of material protected by copyright or other intellectual property rights.
