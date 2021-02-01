# SMB Lua: Game Values in a simple GUI.
This is a FCEUX lua script (BizHawk version soon **;)**) for SMB1 and SMB2J that shows in a simple GUI important and useful values for TASers, such as Mario's horizontal position and speed, and his subpixel position. Working 100% in the vanilla games, for use in TASes for the game. The way it works is by getting the wanted values by the game's ram, and converting them to the GUI.

You are free to report errors and/or suggest new stuff to be added.



Mario **cannot** get any faster than 40 XSP, so here are some speed values for you to know some "limits":

0  - Complete stop, no speed

24 - Fastest walking speed

40 - Fastest running speed



RAM values to Mario's subpixel position get incremented by **16** every time, and after *240* is achieved, it resets to 0 (or 256, i don't know).

Comparison between Pellsson/Sockfolder subpixel values and RAM values:


0 - *0/256*

1 - *16*

2 - *32*

3 - *48*

4 - *64*

5 - *80*

6 - *96*

7 - *112*

8 - *128*

9 - *144*

A - *160*

B - *176*

C - *192*

D - *208*

E - *224*

F - *240*
