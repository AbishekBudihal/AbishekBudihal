# Abishek Budihal

**Electronics engineer · Embedded firmware · Digital design**

I work on AV system design at Online Instruments and build projects in embedded C and Verilog. My work spans register-level firmware, serial interfaces, analog-output hardware, and AXI4-Lite peripheral verification.

Previously, I worked on bare-metal firmware for ARM Cortex-M3 and AVR targets as a Firmware Intern at DRDO NSTL.

[LinkedIn](https://www.linkedin.com/in/abishek-budihal) · [Portfolio](https://abishekbudihal.github.io/)

## MY WORK

### [AXI4-Lite peripherals and DMA control](https://github.com/AbishekBudihal/AXI4-DMA-UVM-Verification-IP)

Verilog register-file peripheral and DMA control front-end, with self-checking HDL testbenches. The register-file tests exercise readback and byte-enable writes; the DMA tests cover register programming, busy/done transitions, interrupt enable, zero-length errors, and repeated starts. The DMA front-end models completion with a counter.

The published testbenches reproduce **14 passing register-file checks** and **11 passing DMA checks** with Icarus Verilog. Coverage is measured against the explicit flags in each testbench.

[RTL](https://github.com/AbishekBudihal/AXI4-DMA-UVM-Verification-IP/blob/main/rtl/axi_lite_slave.v) · [Register-file testbench](https://github.com/AbishekBudihal/AXI4-DMA-UVM-Verification-IP/blob/main/UVM_tb) · [DMA design and tests](https://github.com/AbishekBudihal/AXI4-DMA-UVM-Verification-IP/tree/main/DMA_Front_End_Design)

### [SimStage — AV planning workspace](https://github.com/AbishekBudihal/SimStage_AVcustom_3D_simulator)

A TypeScript application connecting room geometry, equipment placement, signal connections, and bill-of-materials data. Built around the AV design problems I work with: display visibility, equipment positioning, and system connectivity. Its viewing and acoustic calculations are planning estimates with documented assumptions.

[Source and setup](https://github.com/AbishekBudihal/SimStage_AVcustom_3D_simulator) · [Engineering assumptions](https://github.com/AbishekBudihal/SimStage_AVcustom_3D_simulator/blob/main/src/workspace/ENGINEERING.md)

## Technical focus

- **Firmware:** embedded C, AVR/XMEGA, register-level peripheral configuration, SPI and UART.
- **Digital design:** Verilog, AXI4-Lite register interfaces, finite-state machines, self-checking simulation, waveform debugging.
- **System integration:** mixed-signal interfaces, schematics, AV signal chains, equipment selection and BOQ preparation.

Interested in embedded firmware, digital design, and hardware validation roles.
