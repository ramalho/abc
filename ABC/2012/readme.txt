This is the newest version of ABC for Windows/DOS.

It includes:

* the central workspace facility, where all how-to's in the
  workspace called 'abc' are available in all other workspaces.

* archive packing and unpacking:
  abc -w program -p > program.abc

  will 'pack' a workspace called 'program' into a file called program.abc

  Similarly
  abc -w new -u < program.abc

  will 'unpack' the program into a workspace called 'new' (creating it
  if it doesn't already exist).

Unpack the ZIP file in (for instance) C:\Program Files\ABC\
You will find abc.html, a users manual, and abc-qr.html, the ABC quick
reference, as well as abc.exe, and abckeys.exe

When you start ABC, the window will open with the Windows default size
of 25 lines and 80 columns by default; if you want to have a larger
window, go to the file

    C:\WINDOWS\SYSTEM\CONAGENT.EXE

select file>properties (or right-click on the file and select
'properties', or select the file, and type ALT-enter}, click on the
'screen' tab, and select 'initial size', for instance of 50 lines.
Resizing the ABC window will keep the same number of lines, but resize
the font used.

I don't know any way of changing the colours of the screen from white
on black: it seems to be hardwired in the Microsoft terminal emulation.
