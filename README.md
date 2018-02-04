# AITD3-DASM
A project made for disassembling Alone In The Dark 3 (PC CD-Rom) Windows 3.11 (32Bits),
the goal is to understand everything in the engine (function/structure/variable).

it seem that the game was made with Watcom "Watcom v9-*1.5  32bit NT runtime".

## How to play on 64Bits PC the version of Alone In The Dark 3 (PC CD-Rom - Windows 3.11 version)
1) Download WAITD3.EXE from the repo and replace your original executable (this bring patch to the message Queue) fixing animation speed (take note that somehow, if you hold an input key, in the inventory the animation might look 5% faster, idk yet why it does that).

2) wing32.dll (creating Device Context, BitBlt (Bit Block Transfert) for the painting etc). is the 32Bits version that the game is looking for and which is needed in order to play on 64Bits PC.

Download it from the repo and place it in "C:\Windows\SysWOW64".

## Note: This has been tested on Windows 7 only (working perfectly with no bug, the soundtrack as well) it should probably work on windows 10.

# Enjoy !
