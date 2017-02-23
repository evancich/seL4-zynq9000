# seL4_tools

Provides tools used to build seL4 projects

* kbuild-tool: kbuild from Linux, for managing configurations. 
* elfloader-tool: loads the arm kernel.
* common-tool: most of the build system.
* misc: miscellaneous extra tools.

License
-------

Please see files in individual directories for license details. 

Execution
---------
qemu-system-arm -M <<Xilinx Board / CPU Version>> -kernel <<seL4 image file>> -m size=512M -monitor none -nographic -serial /dev/null -serial stdio

Example
-------
qemu-system-arm -M xilinx-zynq-a9 -kernel <<seL4 image file>> -m size=512M -monitor none -nographic -serial /dev/null -serial stdio
