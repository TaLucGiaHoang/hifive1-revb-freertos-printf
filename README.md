# hifive1-revb-freertos-printf

## SiFive HiFive1 Rev B - FreeRTOS
Example for using printf, sprintf on FreeRTOS

The project was modified base on examples code of FreeRTOS demo for HiFive1 Rev B board.
This project was developed by Freedom Studio.

Refer to FreeRTOS/Demo/RISC-V_RV32_SiFive_HiFive1_FreedomStudio in https://sourceforge.net/p/freertos/code/HEAD/tree/trunk/ (r2752)

## Usage
1. Copy files in stdio folder to another FreeRTOS project
  - Demo/RISC-V_RV32_SiFive_HiFive1_FreedomStudiostdio/do_printf.h
  - Demo/RISC-V_RV32_SiFive_HiFive1_FreedomStudiostdio/do_printf.c
  - Demo/RISC-V_RV32_SiFive_HiFive1_FreedomStudiostdio/printf.c
2. Initialize uart0 to print terminal (see main.c)
3. Call printf or sprintf

![Image of Demo](demo.png)