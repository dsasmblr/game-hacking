# [The Ultimate Game Hacking Resource](https://github.com/dsasmblr/game-hacking/)
**A curated list of tutorials and tools for reverse engineering games!**

This repository is dedicated to all things game-hacking, from tools to tutorials to other resources. I'll constantly be updating this list, so be sure to Watch/Star it! If you'd like to share a resource that isn't yet on the list, feel free to submit it for consideration via creating an issue or pull request for this repository, or [email it to me](mailto:dsasmblr@gmail.com).

### Game Hacking Tools (Disassemblers, Debuggers, Hex Editors, Unpackers, Etc.)

Program/Link | Description
---- | ----
[Cheat Engine](https://github.com/cheat-engine/cheat-engine) | A powerful, open-source, all-in-one game hacking tool with an extensive feature set.
[Squalr](https://github.com/Squalr/Squalr) | An open-source, performant game hacking tool developed in C# with features that both rival and complement Cheat Engine.
[CrySearch](http://www.crysearch.nl/) | An open-source memory scanner akin to Cheat Engine, but with different features.
[PINCE](https://github.com/korcankaraokcu/PINCE) | An open-source, front-end/reverse engineering tool for the GNU Project Debugger ([GDB](https://www.gnu.org/software/gdb/)), focused on games. It's essentially a work-in-progress Cheat Engine for Linux/MacOS.
[dnSpy](https://github.com/0xd4d/dnSpy) | An open-source .NET assembly editor and debugger, including support for Unity games (Mono binaries).
[ILSpy](https://github.com/icsharpcode/ILSpy) | An open-source .NET assembly browser and decompiler.
[ReClassEx](https://github.com/dude719/ReClassEx) | An open-source tool that intellgently reconstructs data types. Based on the original [ReClass](https://github.com/CoolOppo/ReClass).
[ReClass.NET](https://github.com/KN4CK3R/ReClass.NET) | An open-source .NET port of ReClass, with many additional features.
[x64dbg](https://x64dbg.com/) | An open-source x86 (32-bit)/x64 (64-bit) debugger for windows. Spiritual successor to [OllyDbg](http://www.ollydbg.de/).
[WinDbg](https://developer.microsoft.com/en-us/windows/hardware/download-windbg) | Microsoft's official Windows debugger which allows for debugging of both kernel and user mode code. There is also a new version of WinDbg being built for Windows 10 ([WinDbg Preview](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/windbg-install-preview)), featuring an updated UI, new features, and more.
[IDA Pro](https://www.hex-rays.com/products/ida/) | A multi-processor disassembler and debugger that works on Windows, Linux, and Mac. This is the crème de la crème of disassemblers in many professional reverse engineer's toolkits. Not freeware.
[HxD Hex Editor](https://mh-nexus.de/en/hxd/) | A fast, free hex editor.
[010 Editor](https://www.sweetscape.com/010editor/) | Extremely powerful and robust hex/text editor. Not freeware.
[Hexinator](https://hexinator.com/) | A worthy "010 Editor" competitor with many different features. Not freeware.
[Exeinfo PE](http://exeinfo.atwebpages.com/) |  A free file packer/compressor detector which provides unpacking info and internal exe tools. A spiritual successor to [PEiD](https://www.aldeid.com/wiki/PEiD).
[Fiddler](https://www.telerik.com/fiddler) | A free web debugging proxy for any browser, system, or platform.
[Wireshark](https://www.wireshark.org/) | A free, robust network protocol analyzer (for tasks much deeper than a web debugging proxy can handle).

### General Information

Title/Link | Description
---- | ----
[EFF FAQ on Reverse Engineering Legalities](https://www.eff.org/issues/coders/reverse-engineering-faq) | This FAQ details information that may help reverse engineers reduce their legal risk. *Use this information as a guide, not actual legal advice.*
*Note: CEF = Cheat Engine Forum* | [Link to Cheat Engine Forum](http://forum.cheatengine.org/)
[CEF Discussion - Memory Alignment](http://forum.cheatengine.org/viewtopic.php?p=5733049&sid=49692077918bd226efaef4452c713825#5733049) |
[CEF Discussion - Mono: Instances and Invoking via Cheat Engine](http://forum.cheatengine.org/viewtopic.php?t=605305) | Short tutorial demonstrating how to use Cheat Engine's Mono features, "Find Instances of Class" and "Invoke Method".
[CEF Discussion - Deallocating Memory in createThread() Script](http://forum.cheatengine.org/viewtopic.php?p=5722316#5722316) | Script examples in x86 and x64 showing how to deallocate memory in a createThread() script.

### Blog Posts, Articles, and Presentations

Title/Link | Description
---- | ----
[Reverse Engineering Visual Novels 101, Part 1](https://hackernoon.com/reverse-engineering-visual-novels-101-d0bc3bf7ab8) | A detailed tutorial on using [Kaitai Struct](http://kaitai.io/) to reverse engineer unknown formats.
[Reverse Engineering Visual Novels 101, Part 2](https://hackernoon.com/reverse-engineering-visual-novels-101-part-2-9258f547262a) | A detailed tutorial on using [Kaitai Struct](http://kaitai.io/) to reverse engineer unknown formats (continued from above).

### Videos

Title/Link | Description
---- | ----
[How to Hack Local Values in Browser-Based Games with Cheat Engine](https://www.youtube.com/watch?v=f_axmYpG1Lk) | This video teaches you how to find and change local values (which might appear as server-based values) in browser-based games.

### Podcasts/Audio

Title/Link | Description
---- | ----
[Darknet Diaries Ep. 7: Manfred Part 1: Hacking Online Video Games for Fun](https://darknetdiaries.com/episode/7/) | "Manfred" has privately been hacking online games for the past 20 years. In this episode, he tells stories of some of the unbelievable ways he's hacked games--all in the name of fun.
[Darknet Diaries Ep. 8: Manfred Part 2: Hacking Online Video Games for Profit](https://darknetdiaries.com/episode/8/) | "Manfred" found a way to turn his passion for video games and reverse engineering into a full time business. He exploited video games and sold virtual goods and currency for real money. This was his full time job. In this episode, he explains exactly how he did this.

### Books

Title/Link | Description
---- | ----
[Game Hacking](https://www.nostarch.com/gamehacking) | *Game Hacking* shows programmers how to dissect computer games and create bots.
[Attacking Network Protocols](https://www.nostarch.com/networkprotocols) | *Attacking Network Protocols* is a deep-dive into network vulnerability discovery.
[Practical Packet Analysis, 3rd Edition](https://www.nostarch.com/packetanalysis3) | *Practical Packet Analysis, 3rd Ed.* teaches you how to use Wireshark for packet capture and analysis.
[Exploiting Online Games: Cheating Massively Distributed Systems](https://www.amazon.com/Exploiting-Online-Games-Massively-Distributed/dp/0132271915/) | This book takes a close look at security problems associated with advanced, massively distributed software in relation to video games.

### Game Hacking Sites/Forums/Etc.

Title/Link | Description
---- | ----
[REGames Subreddit](https://www.reddit.com/r/REGames/) | A subreddit dedicated to reverse engineering video games.
[Reverse Engineering Subreddit](https://www.reddit.com/r/ReverseEngineering) | A subreddit dedicated to reverse engineering in general. Game-related submissions appear quite frequently.
[Guided Hacking](https://guidedhacking.com/) | Discussion of multiplayer and single-player game hacks and cheats.
[UnKnoWnCheaTs Forum](https://unknowncheats.me/) | Discussion of multiplayer game hacks and cheats.
[MPGH (Multi-Player Game Hacking) Forum](http://www.mpgh.net) | Discussion of multiplayer game hacks and cheats.
[ElitePVPers](https://www.elitepvpers.com/) | Discussion of MMO hacks, bots, cheats, guides and more.
[OwnedCore](http://www.ownedcore.com/) | An MMO gaming community for guides, exploits, trading, hacks, model editing, emulation servers, programs, bots and more.

### Open Source and Safe-to-Hack Games

Title/Link | Description
---- | ----
[List of Open Source Games](https://en.wikipedia.org/wiki/List_of_open-source_video_games) | A large list on Wikipedia of open source games, both single-player and multiplayer.
[Pwn Adventure 2](http://ghostintheshellcode.com/#pwnadventure2) | A custom 3D MMOFPS based on the Unity game engine. The game includes several quests that are only solvable by modifying the game client.
[Pwn Adventure 3: Pwnie Island](http://pwnadventure.com/) | A first-person, open-world MMORPG developed specifically to be hacked! You might also be interested in [Pwn Adventure 2](http://ghostintheshellcode.com/#pwnadventure2), which is Unity-based.
[Minetest](http://www.minetest.net/) | An open source, multiplayer voxel-based game and game engine. (A Minecraft clone, basically.)
[Xonotic](http://www.xonotic.org/) | An open source, arena-style multiplayer FPS.
[Nexuiz](http://www.alientrap.com/games/nexuiz/) | The open source, multiplayer FPS game Xonotic is based on.
[AssaultCube](https://assault.cubers.net/) | An open source, multiplayer, FPS.
