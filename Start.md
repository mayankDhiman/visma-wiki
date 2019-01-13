## Launching VisMa

VisMa is currently available in two flavours (GUI and CLI)

For launching **visma** do

```shell
$ visma
```

For entering GUI:

```shell
>>> gui
```
For using CLI you can straight start away by giving commands in following format:

```shell
>>> simplify(12x + 13x^2 + 12 - 10)
INPUT: 12.0x + 13.0x^(2.0) + 12.0 - 10.0
OPERATION: simplify
OUTPUT: 12.0x + 13.0x^(2.0) + 2.0

12.0x + 13.0x^(2.0) + 12.0 - 10.0

12.0x + 13.0x^(2.0) + 2.0
(Adding 12.0 and 10.0)

>>> solve(x^2 - 1,x)
INPUT: x^(2.0) - 1.0 = 0
OPERATION: solve
OUTPUT: x = ( + 1.0)^(0.5)

x^(2.0) - 1.0 = 0

x^(2.0) =  + 1.0
(Moving -1.0 to RHS)

x = ( + 1.0)^(0.5)
(Therefore, x can be written as:)

>>> exit
```

**NOTE:** For windows user (and those for whom) the above launching option is not available to launch **visma** GUI do:

```shell
$ python
>>> from visma.main import initGUI
>>> initGUI()
```


When you will open VisMa for the first time, you will see a window with an editable textbox in the top center, this will be the area where you will be writing your input equation. You will also encounter a list on the left side, the list will save a list of equations you have solved using VisMa, on the right side you will see a grid of buttons, these buttons are to assist you in typing an input, they only support LaTeX style and normal greek style input with very limited buttons, but will updated as VisMa develops.

## Normal Mode
You can type in your input equation/expression in the input field (VisMa has support for only constant powers for now),

`e.g 2x^2/x + 5x^2 - 5 + x = 2 - x`

and press the button Interaction mode, this will populate several buttons, like in this case, simplify, division, addition, subtraction and find roots.
If you press simplify, VisMa will simplify the equation to the simplest form, and show you the step by step animation with comments as to how that stage was achieved. The input area will also be replaced by the final stage i.e. the most simplified stage of the equation.

You can choose to press any of the other buttons like addition, subtraction, division, multiplication. This will only perform all addition or subtraction or division or multiplication operations respectively, at that stage, and show appropriate animation.

Finding roots only support, quadratic roots for now, and it will help you find the quadratic roots of the equation.

## Interaction Mode

You can choose to solve only a part of the input equation/expression. To do this, select only the part of the equation/expression you want simplified, using your mouse cursor, and press interaction mode, and then use one of the available buttons. The buttons will perform the same task as specified above, but only for the selected part of the equation/expression.

## work in progress
