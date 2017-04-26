# JT51
YM2151 clone in verilog. FPGA proven.
(c) Jose Tejada 2016. Twitter: @topapate

Originally posted in opencores. The Github repository is now the main one.

## Folders

* **jt51/doc** contains documentation related to JT51 and YM2151
* **jt51/hdl** contains all the Verilog source code to implement JT51 on FPGA or ASIC
* **jt51/hdl/filter** contains an interpolator to use as first stage to on-chip sigma-delta DACs
* **jt51/syn** contains some use case examples. It has synthesizable projects in various platforms
* **jt51/syn/xilinx/contra** sound board of the arcade Contra. Checkout **hdl** subfolder for the verilog files

## Usage
All files are in **jt51/hdl**. The top level file is jt51.v. You need all files in the **jt51/hdl** folder to synthesize or simulate the design.

Alternatively you can just use the file jt51_v1.1.v at the release folder. It contains all the necessary files concatenated inside. It is generated by the script in bin/jt51_singlefile.sh

## Related projects

* [JT12](https://github.com/jotego/jt12): clone of YM2612
* [JT89](https://github.com/jotego/jt89): clone of SN76489AN
More to come soon!
