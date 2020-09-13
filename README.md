# riscos
My old RISC OS software. Written in ARM "PROG26" 26-bit mode that conveniently stores status flags in the same register (r15) as the PC.

Originally on HENSA and found off of the internet, though I may have a copy on an old hard drive. It will have been archived with *SparkFS*, which can be extracted these days by compiling a copy of [`nspark`](https://github.com/mjwoodcock/nspark).

**DragWindow** is an assembly language module that allows moving, resizing and scrolling (horizontal, vertical or two-way) by clicking anywhere in the window instead of a specific part of the frame. I do miss this, although two-finger scroll/scroll wheels help. It's like a much better version of the earlier memory-hog *MoveWindow* (which also uses a whole one of your 128 pages). This is the original **1024 byte** version (I got it that small and that was enough space optimisation for me). There is a later better effort with command line switches but it is not 1K. Version string is *"DragWindow\t0.01 (15 Oct 1995)"*. I had thought it earlier  - *od1012@uk.ac.bris.seqa* must have been *QuickCaret*.

**QuickCaret** is my assembly language module conversion of *Reuben Thomas's* BASIC program. Again, nobody wants to lose 32K - that's as much memory as an unexpanded Acorn Electron. Version string is *"QuickCaret\t1.01 (12 Jun 1993)"*. *QUICKCARET-SRC.ARC* has 1996-dated files from another author, but it's in BBC BASIC and I haven't detokenised it.
