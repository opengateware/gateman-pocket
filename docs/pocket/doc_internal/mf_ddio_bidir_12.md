# Entity: mf_ddio_bidir_12 

- **File**: mf_ddio_bidir_12.v
## Diagram

![Diagram](mf_ddio_bidir_12.svg "Diagram")
## Ports

| Port name | Direction | Type   | Description |
| --------- | --------- | ------ | ----------- |
| datain_h  | input     | [11:0] |             |
| datain_l  | input     | [11:0] |             |
| inclock   | input     |        |             |
| oe        | input     |        |             |
| outclock  | input     |        |             |
| dataout_h | output    | [11:0] |             |
| dataout_l | output    | [11:0] |             |
| padio     | inout     | [11:0] |             |
## Signals

| Name      | Type        | Description |
| --------- | ----------- | ----------- |
| sub_wire0 | wire [11:0] |             |
| sub_wire1 | wire [11:0] |             |
| dataout_h | wire [11:0] |             |
| dataout_l | wire [11:0] |             |
## Instantiations

- ALTDDIO_BIDIR_component: altddio_bidir
