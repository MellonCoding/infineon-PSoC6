# 2025 ITIS/Bluewind PCTO
**Goals:**
* utilize a Open Source bootloader to flash a 32bit microcontroller (PSoC6 Ai evaluation kit by Infineon)
* load a program in the board and see how does it work

## References
1. [MCUboot homepage](https://docs.mcuboot.com/)
2. [MCUboot github](https://github.com/mcu-tools/mcuboot)
3. [MCUboot infineon guide](https://github.com/mcu-tools/mcuboot/blob/main/boot/cypress/README.md)
4. [ModusToolBox download](https://softwaretools.infineon.com/tools/com.ifx.tb.tool.modustoolboxsetup)

## Report

we started working on the board on monday, we didn't *do* a lot in the first week because the board was completely new to us,
but we managed to understand how to thinker with it, make no mistake, it was everything but easy, 
in order we: read the documentation, tried to install the MTB suite without creating an account, failed to it,
created an account and install the MTB suite, installed eclipse and a lot of tools to play/understand the board,
solved problems, tried to write some programs in C, failed(even if we technically didn't), solved *a lot* of problems
and after 6~7 days; we won, we uploaded (by CLIª) some programs and saw them work, we used putty as a "terminal emulator"
to see the output of the programs (like a console).
until new updated this was from Monda 01/09 to wednesday 10/09.



here are some bullet point on what we did in the 2 weeks to sum up:
- read the docs (way to much times T^T)
- installed all the ModusToolBox tools (MTB setup, programmer, Eclipse [the IDE]) 
    ^^this took **A DAY**, because the MTB suite didn't like Aurora's PC
- created, compiled, and uploaded on the board 2-3 programs 
- erased the board, and made it work again (here we used the programmer tool)
- lost hope
- understood that the Eclipse for MTB has some problemsª
- regained hope
- benched Eclipse for the CLI, for uploading programs, we still build them there because building them from CLI takes too long
- to be continued->




A/ª) the Eclipse for MTB IDE has a problem, or at least we have with it, because every time we tried to load a program 
     into the board, we would have get the same error: "Could not determine GDB version after sending: /Users/user_name/Applications/mtb-gcc-arm-eabi/11.3.1/gcc/bin/arm-none-eabi-gdb --version, response: ", yes, we tried everything (maybe) you can think of, at the end we just uploaded the program by CLI, it works as intended, so this is a win :)
