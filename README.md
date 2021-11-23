# AITD3-DASM (English)
A project made for disassembling Alone In The Dark 3 (PC CD-Rom) Windows 3.11 (32Bits),
the goal is to understand everything in the engine (function/structure/variable).

it seem that the game was made with Watcom "Watcom v9-*1.5  32bit NT runtime".

## How to play on 64Bits PC the version of Alone In The Dark 3 (PC CD-Rom - Windows 3.11 version)
1) Download WAITD3.EXE from the repo and replace your original executable (this bring patch to the message Queue) fixing animation speed (take note that somehow, if you hold an input key, in the inventory the animation might look 5% faster, idk yet why it does that).

2) wing32.dll (creating Device Context, BitBlt (Bit Block Transfert) for the painting etc). is the 32Bits version that the game is looking for and which is needed in order to play on 64Bits PC.

Download it from the repo and place it in "C:\Windows\SysWOW64".

## Note: This has been tested on Windows 7 only (working perfectly with no bug, the soundtrack as well) it should probably work on windows 10.

# Enjoy !

--------------------------------------------------------------------------------------------------------------------------------

# AITD3-DASM (French)
Un projet fait pour désassembler Alone In The Dark 3 (PC CD-Rom) Windows 3.11 (32bits),
le but est de comprendre tout du moteur de jeu (fonctions/structure/variable).

Il semblerait que le jeu est était compiler avec Watcom "Watcom v9-*1.5  32bit NT runtime"

## Comment jouer sur un PC 64Bits Alone In The Dark 3 (PC CD-Rom - Windows 3.11 version)
1) Télécharger WAITD3.EXE depuis le dépot est remplacer votre WAITD3.EXE par celui ci (Sa apporte un patch à la file de message) pour fixé la vitesse des animations (prenez note que bizarrement, si vous garder une touche appuyer, dans l'inventaire la vitesse est 5% plus rapide, je sait pas encore pourquoi.

2) wing32.dll Est en faite utiliser pour: Crée un DC (DeviceContext, BitBlt (Transfert de bloque de bits) est pour peindre. c'est la version 32Bits que le jeu recherche est qui et donc nécéssaire au lancement du jeu sur PC 64Bits.

Télécharger la depuis le dépot est placer la directement dans "C:\Windows\SysWOW64".

## Note: Sa a était testé sur Windows 7 Uniquement (fonctionne parfaitement sans bug, les musiques du CD aussi) sa devrais probablement fonctionner sur windows 10.

# Bon Jeu !
