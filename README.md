# AXI-4 Stream Traffic Generator
The goal of this project is to create a traffic generator peripheral with a slave AXI4-Lite interface and a master AXI-4 streaming interface. Traffic generator comes in handy when we move data from an FPGA to off-chip components such as DDR memory or vice versa, and we would want to verify whether the received data matches the sent data. The traffic generator IP we are going to create consists of a top-level module that instantiates a register module and a stream master module. An AXI-Lite slave interface connected to the register module is used to configure the core.


[Traffic Generator Video Demo](https://photos.app.goo.gl/Y6PoywSLS1v4PKEn6)
