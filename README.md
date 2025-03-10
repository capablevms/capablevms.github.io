# CapableVMs

This [EPSRC](https://epsrc.ukri.org/)-funded research project is part of the DSbD ecosystem. We are investigating how programming language virtual machines (VMs) can make use of hardware capabilities, such as those found in [CHERI](https://www.cl.cam.ac.uk/research/security/ctsrd/cheri/). The project runs from 2020 to ~~2023~~ 2025, as part of the [Digital Security by Design](https://www.ukri.org/innovation/industrial-strategy-challenge-fund/digital-security-by-design/) initiative.

## Partners

The CapableVMs project is co-hosted at [King's College London](https://www.kcl.ac.uk/) and [University of Glasgow](https://www.glasgow.ac.uk). For more information, please contact
[Laurence Tratt](https://tratt.net/laurie/)
or [Jeremy Singer](http://www.dcs.gla.ac.uk/~jsinger/).

## Projects

- CHERI examples and playground -- [repo](https://github.com/capablevms/cheri-examples)
- Boehm-Demers-Weiser garbage collector port for purecap CHERI [WIP] -- [repo](https://github.com/capablevms/bdwgc)
- Function splitter - explore compartmentalisation using CHERI sentries [on hold] -- [repo](https://github.com/capablevms/llvm-function-split)
- ELF compartments - library for compartmentalising ELF binaries [WIP] -- [repo](https://github.com/capablevms/CHERI-ELF-comp)
- MicroPython interpreter port for purecap CHERI -- [repo](https://github.com/glasgowpli/micropython)
- Webkit port for purecap CHERI [WIP] -- [repo](https://github.com/capablevms/webkit)

## Academic Publications

- Secure Scripting with CHERIoT MicroPython  
(March, 2024) [[doi: 10.1145/3708493.3712694](https://doi.org/10.1145/3708493.3712694)]  
*(Small-scale CHERI microcontrollers can now run Python scripts, using our capability-aware MicroPython bytecode interpreter)*
- Morello MicroPython: A Python Interpreter for CHERI  
(October, 2023) [[doi: 10.1145/3617651.3622991](https://doi.org/10.1145/3617651.3622991)]  
*(The C source code of the MicroPython bytecode interpreter needed some tweaking to make it capability-aware, but we did it!)*
- CHERI Performance Enhancement for a Bytecode Interpreter  
(October, 2023) [[doi: 10.1145/3623507.3623552](https://doi.org/10.1145/3623507.3623552)]  
*(Porting systems code to CHERI involves significant performance tuning to minimize the runtime overheads)*
- Capable VMs Project Overview (Poster Abstract)  
(October, 2023) [[doi: 10.1145/3617651.3624308](https://doi.org/10.1145/3617651.3624308)]
- Towards Secure MicroPython on Morello (WIP)  
(June, 2023) [[doi: 10.1145/3589610.3596272](https://doi.org/10.1145/3589610.3596272)]
- Picking a CHERI Allocator: Security and Performance Considerations  
(March, 2023) [[doi: 10.1145/3591195.3595278](https://doi.org/10.1145/3591195.3595278)] [[arXiv](https://arxiv.org/abs/2303.15130)]  
*(CHERI isn't magic fairy dust - just because a memory allocator runs on CHERI doesn't necessarily mean it is secure...)*
- Boehm-Demers-Weiser Garbage Collection on Morello  
(November, 2022) [[doi: 10.1145/3546918.3560808](https://doi.org/10.1145/3546918.3560808)]
- Capability Boehm: Challenges and Opportunities for Garbage Collection with Capability Hardware  
(February, 2022) [[doi: 10.1145/3516807.3516823](https://doi.org/10.1145/3516807.3516823)]  
*(world's first automatic memory manager running on a CHERI platform, with acceptable performance overheads according to our modeling)*

## Blog posts

- [Two stories for "What is CHERI?"](https://tratt.net/laurie/blog/2023/two_stories_for_what_is_cheri.html)
- [How Hard is it to Adapt a Memory Allocator to CHERI?](https://tratt.net/laurie/blog/2023/how_hard_is_it_to_adapt_a_memory_allocator_to_cheri.html)

## Documentation

Our project documentation is openly available. Check out our [documentation repository](https://github.com/capablevms/docs) for details.
