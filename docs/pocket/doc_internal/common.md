# Entity: synch_2 

- **File**: common.v
## Diagram

![Diagram](common.svg "Diagram")
## Generics

| Generic name | Type | Value | Description |
| ------------ | ---- | ----- | ----------- |
| WIDTH        |      | 1     |             |
## Ports

| Port name | Direction | Type             | Description |
| --------- | --------- | ---------------- | ----------- |
| i         | input     | wire [WIDTH-1:0] |             |
| o         | output    | [WIDTH-1:0]      |             |
| clk       | input     | wire             |             |
| rise      | output    | wire             |             |
| fall      | output    | wire             |             |
## Signals

| Name    | Type            | Description |
| ------- | --------------- | ----------- |
| stage_1 | reg [WIDTH-1:0] |             |
| stage_2 | reg [WIDTH-1:0] |             |
| stage_3 | reg [WIDTH-1:0] |             |
## Processes
- unnamed: ( @(posedge clk) )
  - **Type:** always
