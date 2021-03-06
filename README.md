
    Welcome to DINGUX-TI92

Original Author of XTiger

  Tiger is a TI-92 emulator for Linux/x86.  It was originally written by
  Jonas Minnberg and was closed source.  There were two versions: the SVGA
  version and an Xlib version.  Jonas Minnberg has not worked on XTiger
  for quite a while and he gave Misha Nasledov the code and permission 
  to GPL it.

Author of the PSP, GP2X-F100, GP2X-Wiz and DINGUX ports versions

  Ludovic.Jacomme (ludovic.jacomme@gmail.com) also known as Zx-81

  Special thanks to CousinWeb for giving me its TI92 during the PSP 
  port dev.


1. INTRODUCTION
   ------------

  This is a port on DINGUX of the Texas Instruments 92 emulator for 
  X Window Systems : Xtiger.

  This package is under GPL Copyright, read COPYING file for
  more information about it.


2. INSTALLATION
   ------------

  Unzip the zip file, and copy the content of the directory local to your
  SD card.

  TI92+ > v1.1 Roms are not compatible with this emulator !

  For any comments or questions on this version, please visit 
  http://zx81.zx81.free.fr or http://www.gp32x.com/


3. CONTROL
   ------------

3.1 - Virtual keyboard

  In the editor window, press Select to open/close the On-Screen keyboard.

  Use digital stick to choose one of the 9 squares, and use Y, A, X and B to
  choose one of the 4 letters of the highlighted square.

  Select  Disable virtual keyboard
  L/R     Navigate between different keyboard panels 

2.2 - Standard keys

  In the TI92 emulator window, there are three different mapping (standard,
  left trigger, and right Trigger mappings).  You can toggle between while
  playing inside the emulator using the two trigger keys.

    -------------------------------------
    DINGUX        TI-92          (standard)
  
    Y           Backspace
    A           Space 
    X           Escape 
    B           Enter1
    Up          Up
    Down        Down
    Left        Left
    Right       Right

    -------------------------------------
    DINGUX        TI-92    (left)

    Y           Apps   
    A           Diamond 
    X           Hand   
    B           2nd   
    Up          F1
    Down        F2  
    Left        F3   
    Right       F4   

    -------------------------------------
    DINGUX        TI-92    (right)

    Y           (     
    A           )    
    X           Diamond
    B           ,     
    Up          Up
    Down        Down
    Left        Left
    Right       Right

  Press Select to enter in emulator main menu.
  Press Start  open/close the On-Screen keyboard

  In the main menu

    RTrigger   Reset the emulator

    X   Go Up directory
    B   Valid
    A   Valid
    Y   Go Back to the emulator window


3.3 Touch screen

  This version supports the touch screen.

3.3.1 - On the virtual keyboard panel

  Using the touch screen you can click on the letter you want, and drawing a
  line vertically or horizontally (on the virtual keyboard screen) you can
  navigate between the different keyboard panels.

3.3.2 - Editor menu 

  The touch screen can be used to move the cursor on a
  position with a simple click. And then you can :

  draw a line up    : page up
  draw a line down  : page down
  draw a line left  : first column of the current line
  draw a line right : last column of the current line

3.3.3 - Main menu

  You can select the line you want and click to select the option you want.

3.3.4 - File requester menu

  You can use the virtual keyboard as previously described.  If you press the
  touch screen in the first line, current selection goes up, and if you press
  the touch screen in the last line, current selection goes down. You can draw a
  line left / right to do page up / down.

  You can open the file you want by a simple click.

3.3.5 - Help menu

  draw a line up/left     : page up
  draw a line down/right  : page down

3.3.6 - Settings menu

  You can select the line you want and click to select the option you want.
  Just click on left or right part of the menu option name to respectively
  decrease or increase its value.

3.3.7 - Emulator window

  You can use the virtual keyboard as previously described.


4. LOADING TI-92 APPLICATION FILES
   ------------

  You can save any TI 92 files (with .92* file extension) on your 
  SD card. 

  It may happen that the file is not properly loaded, and so you have 
  to try again.

  To manage applications already loaded in your TI-92, you can use 
  the VLINK menu.

  You can find many applications on http://www.ticalc.org/ and on the 
  official TI ftp site ftp://ftp.ti.com/pub/graph-ti/calc-apps/92/


5. LOADING KEY MAPPING FILES
   ------------

  If you want to modify the default keyboard mapping between DINGUX Keys and 
  TI-92 keys you can write your own mapping file. Using notepad for
  example you can edit a file with the .kbd extension and put it in the kbd 
  directory.

  After writting such keyboard mapping file, you can load them using the 
  keyboard menu.


6. COMPILATION
   ------------

  It has been developped under Linux FC9 using gcc with DINGUX SDK. 
  All tests have been done using a Dingoo with Dingux installed
  To rebuild the homebrew run the Makefile in the src archive.

  Enjoy,
  
         Zx
