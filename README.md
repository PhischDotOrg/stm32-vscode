# stm32f4-vscode
Visual Studio Code Settings for working with my STM32F4 Projects.

# What this does
* Sets up CMake Kits for the ARM GCC Cross-Compiler and Toolchain.
* Sets up CMake Variants for the STM32F4 Boards I'm using.
* Installs a Launch Configuration to debug on the embedded target with GDB.
* Provides Build Tasks to start and stop OpenOCD.

All of the above should work on Mac OS, Windows and Linux.

# How to use
Check out / Clone this repository as `.vscode` in a Visual Studio Code Workspace. For example:

`git clone https://github.com/PhischDotOrg/stm32f4-vscode.git .vscode`
