# Cross Compiler

Builds a barebones cross compiler to `$HOME/opt/cross/`.

This script automates the process described on the [OSDev Wiki](http://wiki.osdev.org/GCC_Cross-Compiler).

## Build
`./cross_setup`

Note that texinfo requires an additional command to be fully installed after the script's completion. Check 'WARNING' in the output.

## Add To Path
Either add it manually in your `.bashrc` file (or similar), or run the following command to add to path for the life of the terminal:
`source add\_to\_path`
