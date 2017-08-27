Welcome to the VisMa wiki! This wiki will be divided in 2 section, and will act as both the user guide and the development manual.

# User Guide

## Installation and Running the program

VisMa mainly runs on Python 2.7 and a few supporting libraries like PyQt 4. 
Unfortunately, VisMa is still taking its baby steps hence a pre-compiled package isn't available yet. 
It has some dependencies other than Python 2.7 and PyQt 4, like:
Freeglut 3 (for OpenGL)

PyFTGL (python wrapper for FTGL, it can be built using instructions on the [PyFTGL GitHub repo](https://github.com/umlaeute/pyftgl) )

simplejson

If you are an Ubuntu user, fret not, run.sh script is available for you guys, to setup the environment and run the program for the first time. You simply need to go to the root folder of VisMa and run

`./run.sh`

in your terminal.

**Note**: Installation scripts for other Operating systems is on its way.
If you have already installed all the dependencies for your system, you can go into the root directory of VisMa and run the program by running 

`python main.py`

in your terminal.

