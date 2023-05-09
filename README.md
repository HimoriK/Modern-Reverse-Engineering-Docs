# Modern Reverse Engineering Docs
Modern resources, preferably from at least 2018, outdated resources *must* have results.

## Software & Libraries
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra): Software reverse engineering (SRE) framework created and maintained by the NSA, with tools that analyze compiled code. Capabilities include disassembly, assembly, decompilation, and scripting, along with many other features. Ghidra supports a wide variety of process instruction sets. Users may also develop plug-ins.
* [Capstone](http://www.capstone-engine.org/): Capstone is a lightweight multi-platform, multi-architecture disassembly framework.
* [Radare2](http://www.radare.org/): Portable reversing framework for disassembly, debugging, forensics, etc. Based on capstone, scriptable.
* [x64dbg](http://x64dbg.com/): Open source x64/x32 Windows debugger.

## Basics
* [Reverse Engineering 101](willreplace)
* [CTF Guide](https://trailofbits.github.io/ctf/)

### Books
* [Programming from the Ground Up](https://www.amazon.com/Programming-Ground-Up-Jonathan-Bartlett/dp/1540831825): Uses x86 Linux assembly language for the most important concepts in programming, resources supplied, Princeton University, has complementary book by the author, 2016.
* [Learn to Program with Assembly](https://www.amazon.com/Learn-Program-Assembly-Foundational-Programmers/dp/1484274369): Teaches x86-64 with Linux assembly language, 2021.
* [Reverse Engineering for Beginners](https://beginners.re/): Available in english and russian, good resource for beginners. x86-64, syscalls, etc
* [The Red Book](https://www.red-book.eu/m/documents/syssec_red_book.pdf): Systems security research roadmap, 2013.
* [Ghidra: The Definitive Guide](https://www.amazon.com/product-reviews/1718501021): One of the few resources on the Ghidra reversing tool. 
* [Intro to Compilers & Language Design](https://www3.nd.edu/~dthain/compilerbook/compilerbook.pdf): Brief book on designing a compiler, free.
* [Blue Fox: Arm & Reverse Engineering](https://www.amazon.com/Blue-Fox-Assembly-Internals-Analysis/dp/1119745306): Introduces reverse engineering concepts such as static/dynamic binary analysis
and disassembly/debugging Arm binaries, 2023. (#1 on amazon @ 5 stars, not sure if this is good though)

## Data Structures
* [Automatic Reverse Engineering of Data Structures from Binary Execution](https://www.cs.purdue.edu/homes/xyzhang/Comp/ndss10.pdf) [PDF] 
* [MemPick: High-Level Data Structure Detection in C/C++ Binaries](http://www.cs.vu.nl/~herbertb/papers/mempick_wcre13.pdf) [PDF]

## Exploitation
* [Automated Vulnerability Discovery Techniques](https://docplayer.net/storage/65/53692826/1683335635/qjeAEfhz_QMXEJ-lJUMexg/53692826.pdf) [PDF]
* [Memory Graph Approach for Program Data Introspection and Modification](http://software.imdea.org/~juanca/papers/sigpath_esorics14.pdf) [PDF]

## Instruction Sets
* [Intel® 64 & IA-32 Architectures Manuals](http://www.intel.com/content/www/us/en/processors/architectures-software-developer-manuals.html): Describes environment of Intel® 64 and IA-32.
* [X86 Opcode and Instruction Reference](http://ref.x86asm.net/): Precise opcode and instruction set reference (including x86-64). Contains exact definition of instruction parameters and attributes.
* [X86-64 Reference](http://www.felixcloutier.com/x86/): September 2014 version of Intel® 64 and IA-32 Architectures SDManual, vol 2A and 2B. **Uses [PDF mining](https://github.com/zneak/x86doc) to generate reference from official docs.**

## Malware Analysis
[Refererence](malwareanalysis.md)

## Network

### Other
## Windows
### Patch Guard
* [Disable PatchGuard Windows 8](https://github.com/Fyyre/oldsite/blob/master/bootloader_v2.txt)
* [Disable PatchGuard](https://github.com/Mattiwatti/EfiGuard)
## Mac and iOS
* [iOS App Reverse Engineering](https://github.com/iosre/iOSAppReverseEngineering): iOS App Reverse Engineering is the world's 1st book of very detailed iOS App reverse engineering skills
* [Reversing iOS Apps: A Practical Approach](https://s3.amazonaws.com/s3.synack.com/T2_reversingIOSApps.pdf) [PDF]
## Android

### Extra
* [PeachPy](https://github.com/Maratyszcza/PeachPy): Portable efficient assembly code-generator in higher-level python.
* [Implementing Reverse Engineering](https://www.amazon.com/product-reviews/B09DT5N5JP): I haven't read this, sample seems ok.
* [Game Boy Coding Adventure](https://www.amazon.com/Game-Boy-Coding-Adventure-programming-ebook/dp/B0B7FY5576): Brief but informative game boy hacking book, 2021. 
* [Mastering Defensive Security](https://www.amazon.com/Mastering-Defensive-Security-techniques-infrastructure-ebook/dp/B09BZXC5SC): Random cyber security book.
* [xchg rax,rax](https://www.amazon.com/xchg-rax-xorpd/dp/1502958082): Joke Assembly book.

### Old
* [Intro to Microprocessors and Computer Architecture](https://www.amazon.com/Inside-Machine-Introduction-Microprocessors-Architecture/dp/1593276680): Brief reference, 2007.
* [x86 Instruction Set Architecture](https://www.amazon.com/X86-Instruction-Set-Architecture-Comprehensive/dp/0977087859): Lengthy book on x86 ISA, 2011.
* [Reverse Engineering of Protocols from Network Traces](http://www.di.fc.ul.pt/~nuno/PAPERS/WCRE11.pdf) [PDF]
* [The Art of Unpacking](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf) [PDF]
* [The IDA Pro Book: Unofficial Guide](https://www.amazon.com/IDA-Pro-Book-Unofficial-Disassembler/dp/1593272898): Outdated.
* [Genetic Programming for Reverse Engineering](https://web.eecs.umich.edu/~weimerw/p/weimer-wcre2013-re-preprint.pdf)

## Contribute
Your submissions must be modern, relevant, and have interesting or subjective information.
It cannot simply just be popular or something you read, but have a higher amount of data 
with a high return on investment (no fluff). Videos,books,articles, and sometimes blogs
will be allowed. If it's before 2018, date it with the relevant information. If the data
is outdated or common it will be removed. Information suitable for beginners, intermediates,
preferred, even rare and/or difficult to find research is highly coveted, good luck out there.

Relevant topics:

* C Programming
* x86/64 Architecture
* ARM Assembly
* Windows API *10/Legacy/DOS
* Linux API *Any
* Reverse Engineering
* Game Hacking
