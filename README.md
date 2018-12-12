# PASM_Assembler
The Beaglebone Black PASM assembler available as a compiled binary and as a Visual Studio 2017 C++ project. 

The PASM Assembler is designed to compile PASM Assembly Code (`.p`) files into binaries which can then be run in the Programmable Realtime Units (PRU’s) of the Beaglebone boards. The PASM Assembler consists of a single Windows PASM.EXE executable of about 62Kb in size.

The PASM.EXE binary does not seem to be generally available for download and it appears that users are expected to download the C++ source and compile it up for themselves. This can be troublesome for those who do not have Visual Studio and/or C++ installed. 

The purpose of this project is to provide a compiled PASM.EXE binary and also a Visual Studio 2017 C++ solution in case you wish to compile it up yourself. In reality, if you are compiling the PASM Assembler yourself, you should probably just use the definitive source for these files which is on BeagleBoard GitHub Repo [https://github.com/beagleboard/am335x_pru_package]( https://github.com/beagleboard/am335x_pru_package). 

You can find the PASM.EXE compiled up as a binary in the `Compiled_pasm.exe_As_A_Zipfile.zip` file.

The license for the PASM.EXE and the source code is the original license provided in the original repo. You can find it in the LICENCE.txt file. 

It should be noted that the name *PASM Assembler* is also used for several other Assemblers not in any way related to this one. This assembler is solely and specifically dedicated to building binaries which will run the the Programmable Realtime Units of the Beaglebone series of microprocessors.

