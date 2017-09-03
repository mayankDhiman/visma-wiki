Welcome to the VisMa wiki! This wiki will be divided in 2 section, and will act as both the user guide and the development manual.

# Current Capabilities

Currently, VisMa supports:

* Simplification of expression and equations. You can either choose to step by step perform each of the sub-function i.e. addition, subtraction, multiplication and division or choose to simplify the whole expression/equation at once.

* Finding roots: You can find roots for a quadratic equation.

* VisMa allows you to use interaction mode, in which you can select a part of your expression/equation and run any of the simplification functions above.

Coming Soon:

* Solve for: This feature will allow you to derive the equation for a variable from a given equation. e.g. from x + y = 1, we can get x = 1 - y or y = 1 - x

* Integration: This feature will allow you to integrate an expression.

Future Plans:

* Differentiation: This feature will allow you to differentiate an expression.

* Graph: This feature will allow you to get an interactive 2D or 3D graph, with equation of line or plane plotted on it, for better visualisation.

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

## How to use it 

When you will open VisMa for the first time, you will see a window with an editable textbox in the top center, this will be the area where you will be writing your input equation. You will also encounter a list on the left side, the list will save a list of equations you have solved using VisMa, on the right side you will see a grid of buttons, these buttons are to assist you in typing an input, they only support LaTeX style and normal greek style input with very limited buttons, but will updated as VisMa develops.

### Normal Mode
You can type in your input equation/expression in the input field (VisMa has support for only constant powers for now), 

`e.g 2x^2/x + 5x^2 - 5 + x = 2 - x`

and press the button Interaction mode, this will populate several buttons, like in this case, simplify, division, addition, subtraction and find roots. 
If you press simplify, VisMa will simplify the equation to the simplest form, and show you the step by step animation with comments as to how that stage was achieved. The input area will also be replaced by the final stage i.e. the most simplified stage of the equation. 

You can choose to press any of the other buttons like addition, subtraction, division, multiplication. This will only perform all addition or subtraction or division or multiplication operations respectively, at that stage, and show appropriate animation.

Finding roots only support, quadratic roots for now, and it will help you find the quadratic roots of the equation.

### Interaction Mode 
You can choose to solve only a part of the input equation/expression. To do this, select only the part of the equation/expression you want simplified, using your mouse cursor, and press interaction mode, and then use one of the available buttons. The buttons will perform the same task as specified above, but only for the selected part of the equation/expression.

# Developer Manual
There are comments at the start of each module which explains the utility of the module, comments are being added for each function as well. These comments will include, relevance, how it works, future vision.

**Note**: Please use tabs and not 4/8 spaces. Since Python is a language in which indentation is part of the syntax. We would want it to be consistent among all the developers. If you prefer using spaces, please use 8 spaces, as it will make it usable on terminal text editors like vim and nano. 
