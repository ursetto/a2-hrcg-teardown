# HRCG teardown

This is my attempt to disassemble some of the routines on the DOS Toolkit disk, also known as the Applesoft toolkit. Don Lancaster's Tearing Into Machine Language Code suggests disassembling the Apple Hi-Res Character Generator (HRGC), and I started at the beginning.

So far I've disassembled:

- [RBOOT](RBOOT.html) -- loads and relocates RLOAD
- [RLOAD](RLOAD.html) -- loads and relocates HRCG, APA or other relocatable module

RBOOT/RLOAD are described in `applesoft_toolkit__part_2_.pdf` on Asimov.
HRCG is mostly described in part 1.
