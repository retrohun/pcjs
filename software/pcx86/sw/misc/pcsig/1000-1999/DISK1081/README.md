---
layout: page
title: "PC-SIG Diskette Library (Disk #1081)"
permalink: /software/pcx86/sw/misc/pcsig/1000-1999/DISK1081/
machines:
  - id: ibm5150
    type: pcx86
    config: /machines/pcx86/ibm/5150/cga/256kb/machine.xml
    diskettes: /machines/pcx86/diskettes.json,/disks/pcsigdisks/pcx86/diskettes.json
    autoGen: true
    autoMount:
      B: "PC-SIG Library Disk #1081"
    autoType: $date\r$time\rB:\rDIR\r
---

{% include machine.html id="ibm5150" %}

{% comment %}info_begin{% endcomment %}

## Information about "MODULA-2 COMPILER 2 OF 2 (ALSO 1080)"

    The MODULA-2 COMPILER (M2C) proves you don't have to buy a
    commercial package to get a full-featured compiler!  M2C features the
    compiler combined with an integrated editor and ``make'' facility, a
    program linker, an execution profiler, and a makefile generator.
    
    Code generated by the M2C suits either the Intel 8086 ``huge'' or
    ``large'' memory models.  More restrictive memory models are not
    supported.  For the ``huge'' model, each module has its own data and
    code segment.  Each of the segments can be up to 64K in size.  For the
    ``large'' memory model, static data from all the modules is combined
    into a single data segment.  For either model, pointers are four bytes
    long and all remaining memory is available for the ``heap''.
    
    The package includes 37 pages of well-written and indexed
    documentation.
{% comment %}info_end{% endcomment %}

{% comment %}samples_begin{% endcomment %}

## FILE1081.TXT

{% raw %}
```
Disk No: 1081
Program Title:  MODULA-2 COMPILER version 2.0a (Disk 2 of 2)
PC-SIG version:  2

The MODULA-2 COMPILER (M2C) proves that you don't have to buy a
commercial package to get a full-featured compiler!  M2C features the
compiler combined with an integrated editor, "make" facility, a program
linker, an execution profiler, and a makefile generator.

Code generated by the M2C suits either the Intel 8086 "huge" or "large"
memory model.  More restrictive memory models are not supported.  For
the "huge" model, each module has its own data and code segment.  Each
of the segments can be up to 64K in size.  For the "large" memory model,
static data from all the modules is combined into a single data segment.
For either model, pointers are 4 bytes long and all remaining memory is
available for the "heap."  The package includes 37 pages of indexed
documentation which are well written and understandable.  This is the
second disk in the set, the first is #1080.

Usage:  Modula Programming Utilities.

Special Requirements:  512K memory and the Modula programming language.

How to Start:  Type GO (press enter).

Suggested Registration:  $25.00

File Descriptions:

FM2EXA   ARC  Archived file containing sample files.
FM2LIB20 ARC  Archived file containing library files.

PC-SIG
1030-D East Duane Avenue
Sunnyvale, CA   94086
(408) 730-9291
(c) Copyright 1988,89 PC-SIG, Inc.

```
{% endraw %}

## GO.TXT

{% raw %}
```
╔═════════════════════════════════════════════════════════════════════════╗
║        <<<<  Disk No 1081 MODULA-2 COMPILER (Disk 2 of 2)  >>>>         ║
╠═════════════════════════════════════════════════════════════════════════╣
║ Instert disk #1080 into drive A: and type GO (press enter)              ║
╚═════════════════════════════════════════════════════════════════════════╝
```
{% endraw %}

{% comment %}samples_end{% endcomment %}

### Directory of PC-SIG Library Disk #1081

     Volume in drive A has no label
     Directory of A:\

    FILE1081 TXT      1430   6-27-89   9:56a
    FM2EXA   ARC     25691  11-07-88   9:26p
    FM2LIB20 ARC    146183  11-26-88   9:16p
    GO       BAT        38   6-02-88  10:11a
    GO       TXT       386   6-27-89   3:59p
            5 file(s)     173728 bytes
                          145408 bytes free