# Awesome Tandy CoCo Development[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re) [![Build Status](https://travis-ci.org/dougmasten/awesome-coco.svg?branch=master)](https://travis-ci.org/dougmasten/awesome-coco)

A curated list of awesome Tandy Color Computer development resources, tools, docs and related projects.
Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Contents

- [Community](#community)
- [Documentation](#documentation)
- [Programming](#programming)
- [Project Blogs](#project-blogs)
- [Software Developmnt](#software-development)

## Community

### Conferences

- [Glenside "Last" Chicago CoCoFEST!](http://www.glensideccc.com/)
- [Tandy Assembly](http://www.tandyassembly.com/)

### Email Lists

- [CoCoList](https://pairlist5.pair.net/mailman/listinfo/coco) for Color Computer Enthusiasts

### Facebook

- [TRS-80 Color Computer (CoCo)](https://www.facebook.com/groups/2359462640/)

### Discord

- [TRS-80 CoCo TALK](https://discordapp.com/invite/4J5nHXm)

### Podcasts

- [CoCoTalk! Podcast](http://cocotalk.live/)
- [The CoCo Crew Podcast](http://www.cococrew.org)

## Documentation

- [Motorola 6809 and Hitachi 6309 Programmer's Reference](https://thezippsterzone.com/wp-content/uploads/2018/06/6x09_Instruction_Sets.pdf) by Darren Atkinson

## Software Development

### Assemblers and Compilers

- [CMOC](https://perso.b2b2c.ca/~sarrazip/dev/cmoc.html) - Cross-compiler for a subset of the C language [Documentation](https://perso.b2b2c.ca/~sarrazip/dev/cmoc-manual.html)
- [LWTOOLS](http://lwtools.projects.l-w.ca/) - Cross-development Assembler [Documentation](http://lwtools.projects.l-w.ca/manual/manual.pdf)

### Emulators

- [MAME](http://www.mamedev.org/release.html) - Multiple Arcade Machine Emulator
- [VCC](https://github.com/VCCE/VCC/releases) - Virtual Color Computer Emulator

### Tools

- [CoCo3 RAM Stress Tester](https://github.com/richard42/cocostress)
- [Toolshed](https://github.com/boisy/toolshed) - Cross-development disk images tools [Documentation](http://toolshed.sourceforge.net/ToolShed.html)
- [f9dasm](https://github.com/Arakula/f9dasm) - Disassembler
- [sgeditremix](https://github.com/daftspaniel/sgeditremix) - Web based low-resolution screen designer

### Libraries

- [Docker Development Environment](https://github.com/jamieleecho/coco-dev)
- [Dynosprite](https://github.com/richard42/dynosprite) - Video game engine

### Editor Syntax Highlighting

#### Assembly

- [Atom](https://atom.io/packages/language-6809)
- [Emacs](https://gitlab.com/NF6X_Retrocomputing/lwasm-mode)
- [Notepad++](https://gist.github.com/pfiscarelli/4013e3fd743c41ffa788328fbbb4bfd9)
- [Sublime Text](https://github.com/dougmasten/sublime-assembly-6809)
- [Vim](https://github.com/74hc595/Ultim809/blob/master/code/as6809.vim)
- [Visual Studio](https://marketplace.visualstudio.com/items?itemName=Tandy.6x09-assembly)

#### Color Basic

- [Notepad++](https://gist.github.com/pfiscarelli/4fd32f282c23272c2bd231f0b9d1062a)
- [Visual Studio](https://marketplace.visualstudio.com/items?itemName=Tandy.color-basic)

## Project Blogs

- [CoCo SDC Media Player](https://thezippsterzone.com/2018/05/14/coco-sdc-media-player/) by Ed Snider
- [Cosmic Aliens Development Blogs](http://cosmicaliens.com/development-blog/) by Steve Strowbridge
- [Defender Conversion](https://nowhereman999.wordpress.com/2017/12/31/defender-conversion-for-the-coco-3-part-1/) by Glen Hewlett
- [Donkey Kong Emulator](http://users.axess.com/twilight/sock/dk/index.html) and [Remixed](http://users.axess.com/twilight/sock/dkremix/index.html) by John Kowalski (Sock Master)
- [Gloom-3D Demonstration](http://users.axess.com/twilight/sock/gloom/gloom.html) by John Kowalski (Sock Master)
- [GunStar - Game Development](http://www.nickmarentes.com/Gunstar/index.html) by Nickolas Marentes
- [Pac Man Conversion](https://nowhereman999.wordpress.com/2016/12/29/zilog-z80-to-motorola-6809-transcode-part-001/) by Glen Hewlett
- [PopStar Pilot - Game Development](http://www.nickmarentes.com/PopstarPilot/index.html) by Nickolas Marentes
- [Sock Master's CoCo Demos](http://users.axess.com/twilight/sock/cocofile/demo.html) by John Kowalski (Sock Master)
- [The Making of Fahrfall](http://fahrfall.blogspot.com/) by John Linville

## Programming

### Articles

- [Arcade Machine Conversion Overview](https://nowhereman999.wordpress.com/2018/01/20/arcade-machine-conversion-to-the-coco-overview/) by Glen Hewlett
- [Assembly on a modern computer](https://nowhereman999.wordpress.com/2017/06/19/coco-6809-assembly-on-a-modern-computer/) by Glen Hewlett
- [CoCo Cross Development](https://www.vintageisthenewold.com/coco-cross-development-part-1/) by Allen Huffman
- [CoCo Loaders](http://lost.l-w.ca/0x05/wp-content/uploads/2010/02/Coco-Loaders.pdf) by William Astle
- [Compile C programs using MacOS or Linux](https://nowhereman999.wordpress.com/2016/11/08/compiling-c-programs-for-the-old-radio-shack-trs-80-color-computer-running-under-rsdos-using-macos-or-linux/) by Glen Hewlett
- [How to setup and use IRQs](https://nowhereman999.wordpress.com/2017/11/17/how-to-setup-and-use-irqs-on-the-trs-80-color-computer-part-1-what-is-an-irq-and-when-would-i-use-it/) by Glen Hewlett
- [Make PMODE 4 CSM Video Files](https://nowhereman999.wordpress.com/2017/07/31/how-to-make-pmode-4-csm-video-files-for-the-coco-trs-80-color-computer/) by Glen Hewlett
- [Optimizing 6809 Assembly Code](https://nowhereman999.wordpress.com/2017/09/14/optimizing-6809-assembly-code-part-1-quick-and-easy-changes-to-speedup-your-code/) by Glen Hewlett

### Source Code

- [Color Max Deluxe (1987)](https://github.com/milliluk/colormax) - by Erik Gavriluk and Greg Miller
- [Timberman](https://www.facebook.com/download/254099108593952/tim4_rev_10.asm?hash=AcqjkVkltRC9gaa5) - by Paul Thayer
- [Zenix and Crystal City](https://github.com/gosub-com/Coco) - by Jeremy Spiller


### Videos

- [CMOC, Docker and Dynosprite](https://youtu.be/zn_iLt9j900) - presented by Jamie Cho
- [Programming in BASIC Series](https://www.youtube.com/watch?v=bidwWkEkuSI&list=PLpy5fe6Zd8ccUvxkGHgvLGo70jScz-7wT) - presented by Steve Strow
- [Setting up Assembly Development Environment](https://youtu.be/_HlUVvypbi4) - presented by Paul Fiscarelli
- [Video Game Development](https://youtu.be/6wCLunU_dno) - presented by John Strong
