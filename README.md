# Modern Reverse Engineering Docs
Modern resources, collection curated based on reverse engineering systems (2018+). For beginners and up.
<details>
  <summary>
    
  #### Table of Contents
</summary>

- [Books](#books)
- [Courses](#courses)
- [Tools](#tools)
- [Contribute](#contribute)

Check [external resources](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/blob/main/externalresources.md) + [malware analysis](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/blob/main/malwareanalysis.md) for more.
</details>

## Basics
There are different paths to learn reverse engineering. Any decent CS course involving computer architecture, CTFs, or browsing resources. Don't bother memorizing long libraries and functions, instead try to understand how a target's architecture works. Recommendation: read at least 2 of the books here, build an environment, pick preferred tools, then take a software apart methodically.

<details open><summary>Terms for common tools</summary>
  
- *Debugger* - sequence through program assembly 
- *Disassembler* - retrieves the bulk program assembly 
- *Decompiler* - reverts a program to it's source code (if the source is known)
</details>

* [Reverse Engineering 101](https://intezer.com/blog/malware-analysis/malware-reverse-engineering-beginners/) Start here, if this is too difficult, run.
* [Reverse Engineering 102](https://www.shadowinfosec.io/2018/05/a-gentle-introduction-into-arm-assembly.html) If you can read this, you can learn.
* [Disassembler 101](https://www.geekbits.io/introduction-to-disassemblers/) An overview
* [GDB Quick](https://www.youtube.com/watch?v=xQ0ONbt-qPs) Old school terminal [tactics](https://www-users.cse.umn.edu/~kauffman/tutorials/gdb)
* [x86 Assembly Crash Course](https://sensepost.com/blogstatic/2014/01/SensePost_crash_course_in_x86_assembly-.pdf) 25 pgs, 2013.
* [NASM](https://pacman128.github.io/pcasm/) & [FASM](https://flatassembler.net/)
* [CTF Guide #1](https://trailofbits.github.io/ctf/) [& #2](https://github.com/ctf-wiki/ctf-wiki)

### Books
* [Intro to C and Software Design](https://www-personal.acfr.usyd.edu.au/tbailey/ctext/ctext.pdf) Good, 2005
* [GNU C Intro](https://www.cs.unibo.it/~renzo/doc/C/c.pdf) Complete, can be used as reference
* [Algorithms Design (in C)](https://www.ime.usp.br/~pf/algorithms/) ok book, intermediate concepts, 2018.
* [ModernC for Absolute Beginners](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/12445479/Modern.C.for.Absolute.Beginners.pdf) Not a fan of this version, but it's new.
* [ModernC++ for Absolute Beginners](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11929600/Modern.C%2B%2B.for.Absolute.Beginners.pdf) Efficient.
* [Reverse Engineering for Beginners](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/14155682/RE4B-EN.pdf): Available in multiple languages, good resource for beginners.
* [Programming from the Ground Up](https://www.amazon.com/Programming-Ground-Up-Jonathan-Bartlett/dp/1540831825): x86 Linux key concepts, Princeton, sequel book by author, 2016.
* [Learn to Program with Assembly](https://www.amazon.com/Learn-Program-Assembly-Foundational-Programmers/dp/1484274369): Teaches x86-64 with Linux assembly language, 2021.
* [Blue Fox: Arm & Reverse Engineering](https://www.amazon.com/Blue-Fox-Assembly-Internals-Analysis/dp/1119745306): Introduces binary analysis concepts with Arm, 2023. (#1 on amazon)
* [Computer Science I](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11522155/ComputerScienceOne.pdf)
* [Algorithms Refresh](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11522196/Algorithms-JeffE-BW.pdf) Has notes, references, open source.
* [ARM7-TDMI-manual-pt3](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11522207/ARM7-TDMI-manual-pt3.pdf)
* [Intro to Arm Assembly](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11522212/Introduction.to.Assembly.Language.Programming.From.Soup.to.Nuts.pdf)
* [Ghidra: The Definitive Guide](https://www.amazon.com/product-reviews/1718501021): Key resource on the Ghidra reversing tool.
* [Intro to Compilers & Language Design](https://www3.nd.edu/~dthain/compilerbook/compilerbook.pdf): Brief book on compiler design, free.

### Courses
* [Programming + Data Structures in C](https://codeahoy.com/learn/cprogramming/toc/) neat, good resource?
* [Intro to Algorithms](https://codeahoy.com/learn/analysisofalgorithms/ch1/)
* [Reverse Engineering Malware Unicorn](https://malwareunicorn.org/workshops/re101.html#0)
* [Windows Exploit Development](https://www.securitysift.com/windows-exploit-development-part-1-basics/) 2013, series, will replace later.

<details>
  <summary>
    
  ### Videos
</summary>

* [FreeCodeCamp ARM Tutorial](https://youtu.be/gfmRrPjnEw4) 2 hours, decent probably
* [MIPS Assembly Tutorial](https://youtu.be/BlOLrVo4Nkk?list=PL5b07qlmA3P6zUdDf-o97ddfpvPFuNa5A) rare enthusiasm, might be good
* [Modern C++ Tutorial Series](https://www.youtube.com/playlist?list=PL9GxRn_rQx8Pwe4bMecruWbIEICAsZtgT) Effective dual instructor content
* [C Tutorial Series](https://www.youtube.com/watch?v=zPObUTmiCzk&list=PLA1FTfKBAEX4hblYoH6mnq0zsie2w6Wif&index=3) bloat, decent though; there's also [A full vid](https://youtu.be/ssJY5MDLjlo?t=399)
* [GDB Tutorial](https://youtu.be/svG6OPyKsrw?t=89) ok intro by Waterloo, 1hr
</details>

### Extra
* [PS1 Programming Language](https://retro-programming.com/playstation-one-programming-language/) article on why PS1 used C
* [Lua StackOverflow Guide](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11522164/lua.pdf) Brief, probably not very good
* [Computer Networks](https://intronetworks.cs.luc.edu/current2/ComputerNetworks.pdf) Good book on networks
* [Mastering Defensive Security](https://www.amazon.com/Mastering-Defensive-Security-techniques-infrastructure-ebook/dp/B09BZXC5SC) Random cybersecurity book.

## Tools
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra) NSA Software reverse engineering kit. Includes disassembly, decompilation, etc. Highly extensible.
* [010 Editor](https://www.sweetscape.com/010editor/) Best Proprietary Hex Editor for binary analysis; [Binja](https://binary.ninja/), Free alt is: [HxD](https://mh-nexus.de/en/hxd/), [Bless](https://github.com/afrantzis/bless), or [ImHex](https://github.com/WerWolv/ImHex)
* [x64dbg](http://x64dbg.com/) Open source x64/x32 Windows debugger. [Reko](https://github.com/uxmal/reko) decompiler

### Old
* [Intro to Microprocessors and Computer Architecture](https://www.amazon.com/Inside-Machine-Introduction-Microprocessors-Architecture/dp/1593276680) Brief reference, 2007.
* [The Art of Unpacking](https://www.blackhat.com/presentations/bh-usa-07/Yason/Whitepaper/bh-usa-07-yason-WP.pdf) [PDF]
* [Programming for Humans](https://youtu.be/Mr3WTR0a5SM) literate programming, make code easy to understand as it's written

## Contribute
1. Fork the repo, make a new branch.
2. Make changes within that branch.
3. Commit changes with clear notes and pull request.

Any contributions are appreciated!

Relevant topics: [Table of Contents](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs#table-of-contents)

* C Programming
* x86/64 Architecture/ARM Assembly
* Windows API *10/Legacy/DOS, Linux API
* Reverse Engineering / Game Hacking
