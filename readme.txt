smanage:

A simple file manager for the Mac OS X operating system written in python.


About:

I developed it so that I could run multiple instances of applications at the
same time and cut and paste between them.


Installing:

smanage  is a python3 executable file which can be installed anywhere.  It needs
the following modules.

1. python-magic-bin
2. pathvalidate
3. pyperclip

The first line in the smanage file should point to your python3 installation 
path. The first time it's run it will create a directory called smanage in your
~/.config  directory. In this directory is a file named config_file. It is in
the json format. You can edit this file to change your preferred home directory, 
trash directory, and your file type associations.


Running:

Launch smanage from the command line. You can supply a path to any directory as
an argument. 

The program opens with the current directory displayed at the top. You can copy the 
directory, and paste or type in a new path to change the directory.
 
The top row of buttons are self explanatory with the exception of SETWORK. You 
can also use the standard OS X key shortcuts for select all, copy, and paste.

The buttons on the left side all open commonly used directories. The bottom 
button opens a work directory,  You can navigate to any directory, press the 
SETWORK button, and it will set this button to that directory.

The open folder listings are shown the right of the side buttons. Directories 
are on top followed by files. Double click on a directory to open it. Pressing 
SMAGAGER or TERMINAL will run a new instance of these applications in the 
currently open directory. You can copy and paste between different open 
smanagers.  

Double clicking on a file will open it with it's associated program if one 
exists. If you select a text executable such as a bash script or python script,
and press RUN, the file will be run. 

Deleting files and directories will always send them to the trash folder. If you
open the trash folder and delete anything there, the selection will actually be
permanently deleted.
