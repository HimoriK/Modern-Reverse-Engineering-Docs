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
* [x86 Assembly Crash Course](https://sensepost.com/blogstatic/2014/01/SensePost_crash_course_in_x86_assembly-.pdf) 25 pgs, 2013.
* [NASM](https://pacman128.github.io/pcasm/) & [FASM](https://flatassembler.net/)
* [CTF Guide #1](https://trailofbits.github.io/ctf/) [& #2](https://github.com/ctf-wiki/ctf-wiki)

### Books
* [Intro to C and Software Design](https://www-personal.acfr.usyd.edu.au/tbailey/ctext/ctext.pdf) Good, 2005
* [GNU C Intro](https://www.cs.unibo.it/~renzo/doc/C/c.pdf) Complete, can be used as reference
* [Algorithms Design (in C)](https://www.ime.usp.br/~pf/algorithms/) ok book, intermediate concepts, 2018.
* [ModernC for Absolute Beginners](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/12445479/Modern.C.for.Absolute.Beginners.pdf) Not a fan of this version, but it's new.
* [ModernC++ for Absolute Beginners](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11929600/Modern.C%2B%2B.for.Absolute.Beginners.pdf) Efficient.
* [Reverse Engineering for Beginners](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11470339/RE4B-EN.2023.pdf): Available in multiple languages, good resource for beginners.
* [Programming from the Ground Up](https://www.amazon.com/Programming-Ground-Up-Jonathan-Bartlett/dp/1540831825): Uses x86 Linux assembly language on important concepts in programming, Princeton University, has sequel book by the author, 2016.
* [Learn to Program with Assembly](https://www.amazon.com/Learn-Program-Assembly-Foundational-Programmers/dp/1484274369): Teaches x86-64 with Linux assembly language, 2021.
* [Blue Fox: Arm & Reverse Engineering](https://www.amazon.com/Blue-Fox-Assembly-Internals-Analysis/dp/1119745306): Introduces reverse engineering concepts such as binary analysis
and disassembly with Arm, 2023. (#1 on amazon @ 5 stars, great book on Arm Architecture.)
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

### Extra
* [Implementing Reverse Engineering](https://www.amazon.com/product-reviews/B09DT5N5JP): Haven't read this, sample seems ok.
* [Game Boy Coding Adventure](https://www.amazon.com/Game-Boy-Coding-Adventure-programming-ebook/dp/B0B7FY5576): Brief but informative game boy hacking book, 2021.
* [Lua StackOverflow Guide](https://github.com/HimoriK/Modern-Reverse-Engineering-Docs/files/11522164/lua.pdf) Brief, probably not very good
* [Mastering Defensive Security](https://www.amazon.com/Mastering-Defensive-Security-techniques-infrastructure-ebook/dp/B09BZXC5SC): Random cybersecurity book.

## Tools
* [Ghidra](https://github.com/NationalSecurityAgency/ghidra): Software reverse engineering (SRE) framework by the NSA to analyze compiled code. Includes disassembly, decompilation, scripting, etc. Supports different instruction sets & plug-ins.
* [Radare2](http://www.radare.org/): Portable reversing framework for disassembly, debugging, forensics, etc. Based on capstone, uses cmdline, scriptable.
* [x64dbg](http://x64dbg.com/): Open source x64/x32 Windows debugger.

### Old
* [Intro to Microprocessors and Computer Architecture](https://www.amazon.com/Inside-Machine-Introduction-Microprocessors-Architecture/dp/1593276680): Brief reference, 2007.
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
