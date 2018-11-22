# OpenDiablo2
An open source re-implementation of Diablo 2 in C#

<img src="https://raw.githubusercontent.com/essial/OpenDiablo2/master/Screenshot.png" />

## About this project

This is an attempt to re-create Diablo 2's game engine in C#, and potentially make it cross platform as well. This project does not ship with the assets or content required to work. You must have a legally purchased copy of [Diablo 2](https://us.shop.battle.net/en-us/product/diablo-ii) and its expansion [Lord of Destruction](https://us.shop.battle.net/en-us/product/diablo-ii-lord-of-destruction) installed on your computer in order to run this engine. If you have an original copy of the disks, those files should work fine as well.

Please note that **this game is neither developed by, nor endorsed by Blizzard or its parent company Activision**.

This game is a clean-room implementation based on observations of how the original game works. Aside from the data file formats themselves, we have not and will not reverse engineer the original binaries of the game in an attempt to copy or duplicate intellectual property.

Diablo 2 and its content is ©2000 Blizzard Entertainment, Inc. All rights reserved. Diablo and Blizzard Entertainment are trademarks or registered trademarks of Blizzard Entertainment, Inc. in the U.S. and/or other countries.

ALL OTHER TRADEMARKS ARE THE PROPERTY OF THEIR RESPECTIVE OWNERS.

## Running
When running via VisualStudio, go to the debug tab and specify the following command line options:

`-p "C:\Program Files (x86)\Diablo II"`

Substitute the path with wherever you have installed Diablo 2 and its expansions.
