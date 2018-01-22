# [The Ultimate Game Hacking Resource](https://github.com/dsasmblr/game-hacking/)
***A curated list of tools, tutorials, and much more for reverse engineering video games!***

## Introduction
Welcome to the most comprehensive, unique list of game hacking resources on the web! As you traverse this evergrowing behemoth, you may be surprised to learn that many of the tools, libraries, frameworks, etc. featured herein are not made with hacking games in mind whatsoever. Since game hacking is a branch of reverse engineering in its own right, that means we have a wealth of other types of reverse engineering tools at our disposal which we can repurpose for game hacking.

Beyond the tools, there is a wealth of knowledge to be gleaned from a cornucopia of tutorials, presentations, books, and much more. I'll constantly be updating this list, so be sure to Watch/Star it! If you'd like to share a resource that isn't yet on the list, feel free to submit it for consideration via creating an issue or pull request for this repository, or [email it to me](mailto:dsasmblr@gmail.com).

Finally, if **hacking online games** is a topic of interest for you, I'm also maintaining an extensive curated repository for that subject alone: [The Ultimate Online Game Hacking Resource](https://github.com/dsasmblr/hacking-online-games). You may note a negligible amount of overlap between these two repositories, but by and large, they are complementary to one another. And now, on with the game-hacking goodness!
# 

### Game Hacking Tools (Disassemblers, Debuggers, Hex Editors, Unpackers, and More)

Tool Type | Tool/Link | Description
---- | ---- | ----
**All-In-One** | [Cheat Engine](https://github.com/cheat-engine/cheat-engine) | [Open Source] *A powerful, all-in-one game hacking tool with an extensive feature set. Varying versions for Mac, Linux, and Android can be found [here](http://www.cheatengine.org/downloads.php). CE video tutorials [here](https://www.youtube.com/playlist?list=PLNffuWEygffbbT9Vz-Y1NXQxv2m6mrmHr).*
**All-In-One** | [Squalr](https://github.com/Squalr/Squalr) | [Open Source] *A performant game hacking tool developed in C# with features that both rival and complement Cheat Engine.*
**All-In-One** | [CrySearch](http://www.crysearch.nl/) | [Open Source] *A memory scanner akin to Cheat Engine, but with different features and a cleaner UI.*
**All-In-One** | [PINCE](https://github.com/korcankaraokcu/PINCE) | [Open Source] *A front-end/reverse engineering tool for the GNU Project Debugger ([GDB](https://www.gnu.org/software/gdb/)), focused on games. It's essentially a work-in-progress Cheat Engine for Linux/MacOS.*
**All-In-One** | [Binary Ninja](https://binary.ninja/) | [Commercial] *A reverse engineering platform, hex editor, and interactive graph based disassembler.*
**Disassembler/Debugger** | [x64dbg](https://x64dbg.com/) | [Open Source] *An x86 (32-bit)/x64 (64-bit) debugger for windows. Spiritual successor to [OllyDbg](http://www.ollydbg.de/).*
**Disassembler/Debugger** | [WinDbg](https://developer.microsoft.com/en-us/windows/hardware/download-windbg) | [Freeware] *Microsoft's official Windows debugger which allows for debugging of both kernel and user mode code. There is also a new version of WinDbg being built for Windows 10 ([WinDbg Preview](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/windbg-install-preview)), featuring an updated UI, new features, and more.*
**Disassembler/Debugger** | [IDA Pro](https://www.hex-rays.com/products/ida/) | [Commercial] *A multi-processor disassembler and debugger that works on Windows, Linux, and Mac. This is the crème de la crème of disassemblers in many professional reverse engineer's toolkits.*
**Disassembler/Debugger** | [Hopper](https://www.hopperapp.com/) | [Commercial] *A powerful disassembler, decompiler, and debugger for macOS and Linux.*
**Hex Editor** | [HxD Hex Editor](https://mh-nexus.de/en/hxd/) | [Freeware] *A fast, basic hex editor.*
**Hex Editor** | [010 Editor](https://www.sweetscape.com/010editor/) | [Commercial] *Extremely powerful and robust hex/text editor.*
**Hex Editor** | [Hexinator](https://hexinator.com/) | [Commercial] *A worthy "010 Editor" competitor with many different features.*
**Hex Editor** | [Hex Workshop](http://www.hexworkshop.com/) | [Commercial] *A popular, feature-rich hex editor.*
**.NET Decompiler/Debugger** | [dnSpy](https://github.com/0xd4d/dnSpy) | [Open Source] *A .NET assembly editor and debugger, including support for Unity games (Mono binaries).*
**.NET Decompiler** | [ILSpy](https://github.com/icsharpcode/ILSpy) | [Open Source] *A .NET assembly browser and decompiler.*
**Java Decompiler** | [JD-GUI](http://jd.benow.ca/) | [Freeware] *Displays Java source codes of “.class” files. You can browse the reconstructed source code with for instant access to methods and fields.*
**Java Decompiler** | [Helios](https://github.com/helios-decompiler/standalone-app) | [Open Source] *An all-in-one Java reverse engineering tool, featuring integration with the latest, up-to-date decompilers (Krakatau, Fernflower, CFR, Procyon, Javap, etc.).*
**Java Decompiler/Debugger** | [Bytecode Viewer](https://github.com/Konloch/bytecode-viewer) | [Open Source] *A Java 8 Jar and Android APK reverse engineering suite (decompiler, editor, debugger, and more).*
**Java Editor** | [Recaf](https://github.com/Col-E/Recaf) | [Open Source] *Used to edit the binary of java games/apps without needing a hex editor or having to decompile and recompile classes.*
**Flash Decompiler** | [JPEXS](https://github.com/jindrapetrik/jpexs-decompiler) | [Open Source] *Extract resources, convert SWF to FLA, edit ActionScript, replace resources, and more. Works on Windows, Linux, and macOS.*
**Flash Decompiler** | [Trillix](http://www.flash-decompiler.com/) | [Commercial] *Converts SWF to FLA and decompiles Flash (supports Flash up to CS6 & CC and ActionScript 3.0).*
**Java Deobfuscator** | [Deobfuscator](https://github.com/java-deobfuscator/deobfuscator) | [Open Source] *An all-in-one Java deobfuscator which will deobfuscate code obfuscated by most obfuscators available on the market. Accompanying GUI [here](https://github.com/java-deobfuscator/deobfuscator-gui).*
**Network/Traffic Inspector** | [Fiddler](https://www.telerik.com/fiddler) | [Freeware] *A powerful web debugging proxy for any browser, system, or platform.*
**Network/Traffic Inspector** | [Wireshark](https://www.wireshark.org/) | [Freeware] *A robust network protocol analyzer.*
**Network/Traffic Inspector** | [Microsoft Message Analyzer](https://www.microsoft.com/en-us/download/details.aspx?id=44226) | [Freeware] *Enables you to capture, display, and analyze protocol messaging traffic--as well as trace and assess system events and other messages from Windows components.*
**Process Inspector** | [Sysinternals - Process Monitor](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon) | [Freeware] *An advanced monitoring tool for Windows that shows real-time file system, Registry and process/thread activity. Part of the [Windows Sysinternals](https://docs.microsoft.com/en-us/sysinternals/) tool suite.*
**Process Inspector** | [Sysinternals - Process Explorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer) | [Freeware] *Details information about which handles and DLLs processes have opened or loaded. Discover files/directories a program has open, etc. Part of the [Windows Sysinternals](https://docs.microsoft.com/en-us/sysinternals/) tool suite.*
**Process Inspector** | [Process Hacker](https://wj32.org/processhacker/index.php) | [Open Source] *A powerful, multi-purpose tool that helps you monitor system resources and debug software.*
**Process Inspector** | [WinExplorer](http://www.nirsoft.net/utils/winexp.html) | [Open Source] *Shows all of a system's windows and their properties, like handle, class name, caption, size, position, and more. Can modify certain properties for outcomes like making a game run in windowed mode in which it isn't a built-in feature.*
**Function Inspector** | [CDA: Code Dynamic Analysis](http://split-code.com/cda.html) | [Freeware] *Tool for recording, filtering, and hacking function calls within applications or games. x86 support only. Previously open-source and known as [FunctionHacker](https://github.com/glmcdona/FunctionHacker). Tutorial video [here](https://www.youtube.com/watch?v=P0UXR861WYM).*
**Function/API Inspector** | [API Monitor](http://www.rohitab.com/apimonitor) | [Freeware] *Allows you to monitor and control API calls made by applications and services.*
**Function/API Inspector** | [SpyStudio](https://www.nektra.com/products/spystudio-api-monitor/) | [Freeware] *Shows and interprets calls, displaying the results in a structured way. Details registry keys and files that an application uses, COM objects, windows the application has created, errors and exceptions, and more. Tutorials [here](http://whiteboard.nektra.com/spystudio-2-0-quickstart).*
**Function/API Inspector** | [Spy++](https://docs.microsoft.com/en-us/visualstudio/debugger/introducing-spy-increment) | [Freeware] *A powerful tool allowing you to--among other things--spy on messages to/from selected windows in applications.* NOTE: Spy++ is included with [Visual Studio](https://www.visualstudio.com/) (including the free version, [Community](https://www.visualstudio.com/vs/community/)), but can be ran as a standalone tool. Video tutorial [here](https://www.youtube.com/watch?v=WL8rk7pNGo0).
**File Inspector** | [Exeinfo PE](http://exeinfo.atwebpages.com/) | [Freeware] *File packer/compressor detector which provides unpacking info and internal exe tools. A spiritual successor to [PEiD](https://www.aldeid.com/wiki/PEiD).*
**.NET Deobfuscator/Unpacker** | [de4dot](https://github.com/0xd4d/de4dot) | [Open Source] *A .NET deobfuscator and unpacker written in C#. Most obfuscation from supported implementations can be completely restored (eg. string encryption), but symbol renaming is impossible to restore since the original names aren't (usually) part of the obfuscated assembly.*
**Data Type/Structure Reconstructor** | [ReClassEx](https://github.com/dude719/ReClassEx) | [Open Source] *A tool that intellgently reconstructs data types. Based on the original [ReClass](https://github.com/CoolOppo/ReClass).*
**Data Type/Structure Reconstructor** | [ReClass.NET](https://github.com/KN4CK3R/ReClass.NET) | [Open Source] *A .NET port of ReClass, with many additional features. Video tutorials [here](https://www.youtube.com/playlist?list=PLO246BmtoITanq3ygMCL8_w0eov4D8hjk).*
**File Format Parser** | [QuickBMS](http://aluigi.altervista.org/quickbms.htm) | [Open Source] *An extensive tool that parses file formats and extracts/reimports files and archives.*
**File Format Parser** | [MultiEx Commander](http://multiex.xentax.com/) | [Freeware] *Allows you to use and create scripts to extract/import files from/to game resource archives.*
**PE Inspector** | [CFF Explorer](http://www.ntcore.com/exsuite.php) | [Freeware] *Features include dependency walking, disassembly, hex editing, signature scanning/management, special fields description and modification (.NET supported), import adding, extension support, scripting, and more.*
**Firmware/File Analyzer** | [Binwalk](https://github.com/ReFirmLabs/binwalk) | [Open Source] *Binwalk is a fast, easy to use tool for analyzing, reverse engineering, and extracting firmware images. Also extremely useful for game analysis (finding/extracting images from resources, etc.).*
**Text/Binary Pattern Scanner** | [YARA](https://github.com/virustotal/yara) | [Open Source] *Create descriptions of, and rules based on, textual or binary patterns. Excellent for creating custom rules for tasks like identifying resources in a game, game engine and version being used for a game, etc. See [YARA GUI](https://github.com/sigint9/yaragui) for a Windows GUI front-end. Also, see [yarGen](https://github.com/Neo23x0/yarGen) for a YARA rule generator.*
**Injector** | [Xenos](https://github.com/DarthTon/Xenos) | [Open Source] *A Windows DLL injector, based on the [Blackbone library](https://github.com/DarthTon/Blackbone).*
**Compiler** | [Compiler Explorer](https://github.com/mattgodbolt/compiler-explorer) | [Open Source] *Run compilers interactively from your web browser and interact with the assembly!*
**Memory Scanner/Tracer** | [PSR (Pointer Sequence Reverser)](https://github.com/nccgroup/psr/) | [Open Source] *Traces instructions executed prior to reading/writing from/to the provided address of a data member or object, then highlights relevant instructions, identifies vtable pointers, and more. Relevant whitepaper [here](https://www.nccgroup.trust/us/our-research/automated-reverse-engineering-of-relationships-between-data-structures-in-c-binaries/?research=Whitepapers).*
**Memory Scanner/Data Structure Scanner** | [XenoScan](https://github.com/nickcano/XenoScan) | [Open Source] *Lua scriptable memory scanner written in C++. Supports complex scanning, custom structures, and automatic detection of complex structures (linked lists, binary tress, class instances, etc). Expandable with support for emulators. DEFCON Slides [here](https://github.com/nickcano/XenoScanSlides).*

### Libraries, Frameworks, Plugins/Add-ons/Extensions, Etc.

Title/Link | Description
---- | ----
[Lighthouse](https://github.com/gaasedelen/lighthouse) | Code coverage plugin for IDA Pro. The plugin leverages IDA as a platform to map, explore, and visualize externally collected code coverage data when symbols or source may not be available for a given binary.
[Kaitai Struct](http://kaitai.io/) | A declarative language used to describe various binary data structures in files or memory (binary file formats, network stream packet formats, etc.). Allows for development of custom parsers for binary structures.
[Frida](http://frida.re/) | Allows you to inject snippets of JavaScript or your own library into native apps on Windows, macOS, GNU/Linux, iOS, Android, and QNX. Also provides custom, modifiable tools built on top of the Frida API.
[Volatility](https://github.com/volatilityfoundation/volatility) | An open source, advanced memory forensics framework used for the extraction of digital artifacts from volatile memory (RAM) dumps. Great for exploring RAM dumps of running games!
[radare2](https://github.com/radare/radare2) | A portable reverse engineering framework that acts as a forensics tool, scriptable command line hex editor, binary analyzer, disassembler, debugger, and much more. An accompanying open source book on radare2 can be found [here](https://radare.gitbooks.io/radare2book/content/).
[angr](https://github.com/angr/angr) | A suite of python libraries that let you load a binary and perform a whole host of tasks: Disassembly and intermediate-representation lifting, program instrumentation, symbolic execution, control-flow analysis, data-dependency analysis, value-set analysis (VSA), and more.
[CeAutoAsm-x64dbg](https://github.com/atom0s/CeAutoAsm-x64dbg) | An x64dbg plugin that allows users to execute Cheat Engine auto assembler scripts within x64dbg.
[CEAutoAttach](https://github.com/mrexodia/CEAutoAttach) | An x64dbg add-on allowing you to automatically make Cheat Engine attach to a process.
[SignatureScanner](https://github.com/LiamKarlMitchell/SignatureScanner) | A C++-based signature scanning library.
[Hacklib](https://bitbucket.org/rafzi/hacklib) | A C++ library for building applications that run as a shared library in another application. It provides general purpose functionality like pattern scanning, hooking, and laying out foreign classes. Additionally it contains some D3D and OpenGL drawing facilities and a cross-platform, high-performance, 3D-capable, transparent overlay.
[Blackbone](https://github.com/DarthTon/Blackbone) | A Windows x86/x64 hacking library. Visit the repo to learn of its copious features!
[PolyHook](https://github.com/stevemk14ebr/PolyHook) | An x86/x64 hooking library that provides an abstract C++ 11 interface for various hooking methods.
[mhook](https://github.com/martona/mhook) | A Windows API hooking library.
[minhook](https://github.com/TsudaKageyu/minhook) | A minimalistic x86/x64 API hooking library for Windows.
[memory.dll](https://github.com/erfg12/memory.dll) | C# hacking library used for making PC game trainers.
[MemorySharp](https://github.com/ZenLulz/MemorySharp) | C#-based memory editing library targeting Windows applications, offering various functions to extract and inject data and codes into remote processes to allow interoperability.
[Cecil](https://github.com/jbevain/cecil) | A library to inspect, modify, and generate .NET programs and libraries.
[xAnalyzer](https://github.com/ThunderCls/xAnalyzer) | An advanced static code analyzer plug-in for x64dbg.
[AntiDBG](https://github.com/cetfor/AntiDBG) | A categorized collection of Windows anti-debugging techniques written in C. These are self-contained debugger checks that will automatically detach debuggers. Great for learning anti-debugging techniques that might be used in games!
[al-khaser](https://github.com/LordNoteworthy/al-khaser) | A proof-of-concept application that performs a whole slew of detection methods (virtual machine, emulation, debuggers, sandbox) with the goal of seeing if you can stay undetected. Great for learning how to stay hidden from anti-cheat implementations!
[RAM Watch](https://github.com/yoshifan/ram-watch-cheat-engine) | A Lua script framework used to create displays for watching RAM via Cheat Engine. See it in action [here](https://www.youtube.com/watch?v=Hri8f8Pgim8).
[Noriben](https://github.com/Rurik/Noriben) | A Python-based script that works in conjunction with [Windows Sysinternals Process Monitor](https://docs.microsoft.com/en-us/sysinternals/downloads/procmon) to automatically collect, analyze, and report (via a simple text file) on an application or game's activities.
[CyberChef](https://github.com/gchq/CyberChef) | A simple, intuitive web app for carrying out various "cyber" operations, including simple encoding like XOR or Base64, more complex encryption like AES, DES and Blowfish, creating binary and hexdumps, compression and decompression of data, calculating hashes and checksums, IPv6 and X.509 parsing, changing character encodings, and much more. An in-browser, live demo can be found [here](https://gchq.github.io/CyberChef/).
[Deviare API Hook](https://www.nektra.com/products/deviare-api-hook-windows/) | A professional open source hooking engine for instrumenting arbitrary Win32 functions, COM objects, and functions which symbols are located in program databases (PDBs). It can intercept unmanaged code in 32-bit and 64-bit applications.
[Microsoft Detours](https://www.microsoft.com/en-us/research/project/detours/) | A software package for re-routing Win32 APIs underneath applications. 32-bit-only version is free.
[Deviare In-Process](https://www.nektra.com/products/deviare-api-hook-windows/deviare-in-process/) | A code interception engine for Windows (a free-for-non-commercial-use alternative to Microsoft Detours). This library is coded in C++ and provides all the facilities required to instrumenting binary libraries during runtime. Supports x86 and x64 applications.
[AutoIt](https://www.autoitscript.com/site/autoit/) | AutoIt is a freeware BASIC-like scripting language designed for automating the Windows GUI and general scripting. It uses a combination of simulated keystrokes, mouse movement and window/control manipulation in order to automate tasks.
[ReShade](https://github.com/crosire/reshade) | An advanced, fully generic post-processing injector for games and video software. Contains a wealth of information for how to intercept DX/OpenGL APIs and inject custom code (e.g. call your own code at present time when a frame is rendered).
[Injectable Generic Camera System](https://github.com/FransBouma/InjectableGenericCameraSystem) | Used for creating custom camera tools in games. Also contains small tools, like a custom DLL injector to bypass Windows Defender detection.

### Interesting Repositories, Trainer and Custom Tool Source Code, Etc.

Title/Link | Description
---- | ----
[makin](https://github.com/secrary/makin) | A tool to help reveal which debugger detection techniques a game is using.
[JRemapper](https://github.com/Col-E/JRemapper) | An easy-to-use GUI for remapping classes, methods, and fields of compiled java programs. Useful with games like Minecraft!
[Portal 2 Trainer](https://github.com/RedMage1993/Portal2Hack) | A hack/trainer for Portal 2 that demonstrates C++ and Win32 programming, including GUI, multithreading, and external/remote process memory manipulation.
[Game Hacking (Book) Code Repo](https://github.com/GameHackingBook/GameHackingCode) | This is the code repo for all the targets and samples used for the book, [Game Hacking](https://www.nostarch.com/gamehacking).
[pdbWriter](https://github.com/SuperIronBob/pdbWriter) | A small tool to produce a dummy pdb for an executable with symbols at addresses from a file (think: porting work from, say, IDA to be used for dynamic analysis via Cheat Engine, which would apply the symbols from your custom PDB).
[xortool](https://github.com/hellman/xortool) | A tool to analyze multi-byte xor cipher and guess key length (based on count of equal chars) and key (based on knowledge of most frequent char).
[GameTutorials](https://github.com/gametutorials/tutorials) | An expansive list of game development tutorials in multiple langauges. Heavy on source code and even inclusive of Win32 examples (which is an amazing resource if developing Win32 game trainers is of interest to you). Archive of accompanying site [here](http://web.archive.org/web/20150330082829/http://www.gametutorials.com:80/).

### General Information

Title/Link | Description
---- | ----
[EFF FAQ on Reverse Engineering Legalities](https://www.eff.org/issues/coders/reverse-engineering-faq) | This FAQ details information that may help reverse engineers reduce their legal risk. *Use this information as a guide, not actual legal advice.*

### Blog Posts, Articles, and Presentations

Title/Link | Description
---- | ----
[Hack.lu 2017: (Workshop) Reverse Engineering a MMORPG](https://www.slideshare.net/AntoninBeaujeant/reverse-engineering-a-mmorpg) | This workshop covers the basics of reverse engineering a (M)MORPG. The target is [Pwn Adventure 3](http://www.pwnadventure.com/), an intentionally-vulnerable MMORPG developed by [Vector35](https://vector35.com/).
[Reverse Engineering Visual Novels 101, Part 1](https://hackernoon.com/reverse-engineering-visual-novels-101-d0bc3bf7ab8) | A detailed tutorial on using [Kaitai Struct](http://kaitai.io/) to reverse engineer unknown formats.
[Reverse Engineering Visual Novels 101, Part 2](https://hackernoon.com/reverse-engineering-visual-novels-101-part-2-9258f547262a) | A detailed tutorial on using [Kaitai Struct](http://kaitai.io/) to reverse engineer unknown formats (continued from above).
[Exploiting Game Engines for Fun and Profit](http://revuln.com/files/Ferrante_Auriemma_Exploiting_Game_Engines.pdf) | This slide deck shows you methods to exploit game engines, effictively discovering attack vectors that will work across multiple games using the same engine.
[Hooking LuaJIT](https://nickcano.com/hooking-luajit/) | A blog post demonstrating how hooking into a game's scripting engine (in this case, LuaJIT) can expedite the reversing process and enable side-loading of custom scripts.
[Reversing LoL Client w/ Custom API Monitor Definitions](https://nickcano.com/reversing-league-of-legends-client/) | This quick blog post shows how [custom rules](https://github.com/nickcano/LibCEF-API-Monitor-Definitions/blob/master/LibCEF.xml) for [API Monitor](http://www.rohitab.com/apimonitor) can be utilized to aid in the reversing process.

### Interesting/Educational Forum Discussions

Title/Link | Description
---- | ----
*Note: CEF = Cheat Engine Forum* | [Link to Cheat Engine Forum](http://forum.cheatengine.org/)
[CEF Discussion - Memory Alignment](http://forum.cheatengine.org/viewtopic.php?p=5733049&sid=49692077918bd226efaef4452c713825#5733049) | General discussion of memory alignment.
[CEF Discussion - Mono: Instances and Invoking via Cheat Engine](http://forum.cheatengine.org/viewtopic.php?t=605305) | Short tutorial demonstrating how to use Cheat Engine's Mono features, "Find Instances of Class" and "Invoke Method".
[CEF Discussion - Deallocating Memory in createThread() Script](http://forum.cheatengine.org/viewtopic.php?p=5722316#5722316) | Script examples in x86 and x64 showing how to deallocate memory in a createThread() script.
[Reverse Engineering of a Packet Encryption Function of a Game](https://reverseengineering.stackexchange.com/questions/8816/reverse-engineering-of-a-packet-encryption-function-of-a-game) | An informative discussion from a question on StackExchange.

### Videos

Title/Link | Description
---- | ----
[Introduction to IDA Pro (x86/x64, via Windows)](https://www.youtube.com/watch?v=cGDcTSCB7y4) | A well-paced, cursory overview of IDA Pro. It's given in the context of malware analysis, but everything you learn can be directly applied to game hacking.
[Introduction to IDA Pro (ARM, via Mac)](https://www.youtube.com/watch?v=wwo9KjVg-HY) | An example-laden overview of reverse engineering ARM binaries via IDA Pro. It's given in the context of malware analysis, but everything you learn can be directly applied to game hacking.
[Motherboard Livestream Archive: Researcher Cracks Elder Scrolls Online, Dark Age of Camelot, and Wildstar](https://www.youtube.com/embed/iYTCBPUn98c?start=186&end=6620) | Adrian Bednarek, better known as "Manfred", demonstrates the MMORPG hacks he wanted to show but couldn't during [his DEF CON 25 presentation](https://tknk.io/DScz). This is a rare glimpse into the tools, thoughts, and approaches of a professional online game hacker!
[Hacking Games in a Hacked Game](https://vimeo.com/132900706) | This video discusses goes over the results of those who solved CTF challenges in Pwn Adventure 3 at [Ghost in the Shellcode 2015](http://ghostintheshellcode.com/). Slides [here](https://github.com/Vector35/HackingGames).
[The Security of Classic Game Consoles](https://www.youtube.com/watch?v=jkl5NJrRKgA) | A presentation demonstrating the technical details of what went into protecting the security of classic game consoles, as well as how those protections were broken.
[Cracking Video Game Passwords, Season 1](https://www.youtube.com/watch?v=0eQyYrSQPew&list=PLzLzYGEbdY5nEFQsxzFanSDv_38Hz0w7B) | A playlist demonstrating the password schemes used in numerous classic video games.
[Sega Saturn - Cracked After 20 Years](https://www.youtube.com/watch?v=jOyfZex7B3E) | A detailed look into what it took to finally defeat Sega Saturn's protection.

### Books

Title/Link | Description
---- | ----
[Game Hacking](https://www.nostarch.com/gamehacking) | *Game Hacking* shows programmers how to dissect computer games and create bots.
[Attacking Network Protocols](https://www.nostarch.com/networkprotocols) | *Attacking Network Protocols* is a deep-dive into network vulnerability discovery.
[Practical Packet Analysis, 3rd Edition](https://www.nostarch.com/packetanalysis3) | *Practical Packet Analysis, 3rd Ed.* teaches you how to use Wireshark for packet capture and analysis.
[Exploiting Online Games: Cheating Massively Distributed Systems](https://www.amazon.com/Exploiting-Online-Games-Massively-Distributed/dp/0132271915/) | This book takes a close look at security problems associated with advanced, massively distributed software in relation to video games.
[Game Programming Patterns](https://github.com/munificent/game-programming-patterns) | A collection of game patterns that make code cleaner, easier to understand, and faster. A great reference for seeing forward engineering representations of what you discover while reverse engineering games!

### Game Hacking Sites/Forums/Etc.

Title/Link | Description
---- | ----
[REGames Subreddit](https://www.reddit.com/r/REGames/) | A subreddit dedicated to reverse engineering video games.
[Reverse Engineering Subreddit](https://www.reddit.com/r/ReverseEngineering) | A subreddit dedicated to reverse engineering in general. Game-related submissions appear quite frequently.
[Reverse Engineering on StackExchange](https://reverseengineering.stackexchange.com/search?tab=newest&q=Game) | A link to all game-related discussions (sorted by newest) on the RE StackExchange site.
[Cheat Engine Forum (CEF)](http://forum.cheatengine.org/) | The official forum for Cheat Engine.
[FearLess Cheat Engine](http://fearlessrevolution.com/) | Cheat Engine cheat tables, discussions, and tutorials for game hacking.
[Guided Hacking](https://guidedhacking.com/) | Discussion of multiplayer and single-player game hacks and cheats.
[UnKnoWnCheaTs Forum](https://unknowncheats.me/) | Discussion of multiplayer game hacks and cheats.
[MPGH (Multi-Player Game Hacking) Forum](http://www.mpgh.net) | Discussion of multiplayer game hacks and cheats.
[ElitePVPers](https://www.elitepvpers.com/) | Discussion of MMO hacks, bots, cheats, guides and more.
[OwnedCore](http://www.ownedcore.com/) | An MMO gaming community for guides, exploits, trading, hacks, model editing, emulation servers, programs, bots and more.

### Open Source and Safe-to-Hack Games

Title/Link | Description
---- | ----
[List of Open Source Games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) | A large list on Wikipedia of open source games, both single-player and multiplayer.
[Pwn Adventure Z](https://github.com/Vector35/PwnAdventureZ) | An NES zombie survival game made to be hacked.
[Pwn Adventure 2](http://ghostintheshellcode.com/#pwnadventure2) | A custom 3D MMOFPS based on the Unity game engine. The game includes several quests that are only solvable by modifying the game client.
[Pwn Adventure 3: Pwnie Island](http://pwnadventure.com/) | A first-person, open-world MMORPG developed specifically to be hacked!
[Minetest](http://www.minetest.net/) | An open source, multiplayer voxel-based game and game engine. (A Minecraft clone, basically.)
[Xonotic](http://www.xonotic.org/) | An open source, arena-style multiplayer FPS.
[Nexuiz](http://www.alientrap.com/games/nexuiz/) | The open source, multiplayer FPS game Xonotic is based on.
[AssaultCube](https://assault.cubers.net/) | An open source, multiplayer, FPS.
