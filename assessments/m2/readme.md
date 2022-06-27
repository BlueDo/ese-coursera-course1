## Installation
### Install gcc-arm-none-eabi
```
sudo apt-get update
sudo apt-get install gcc-arm-none-eabi
```
Note that the command is `arm-none-eabi-gcc`, different from the package name

## Unsolved Problems
Following files are not incorporated into compilation command:
 - interrupts_msp432p401r_gcc.c
 - startup_msp432p401r_gcc.c
 - system_msp432p401r.c
`objdump` on assembly files