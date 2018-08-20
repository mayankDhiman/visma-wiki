This is a quick guide for getting started with visma. To dive deeper into any specific topic, refer the respective page from the sidebar.

## Contents

- [About](#about)
- [Installation](#installation)
- [Features](#features)
- [Using visma](#using-visma)
- [Developer Guide](#developer-guide)


## About

**VISualMAth** is an equation solver and visualizer, which aims to help in grasping how mathematical equations are transformed and solved. By this the threshold for obtaining deeper mathematical understanding can be reduced. The project aims to help people solve complex problems and learn. It can help students in learning concepts. It can be used as a simple day-to-day calculator or for double-checking the solution to problems.


**NOTE:** VISualMAth is supported for **python3** and above only. The recommended installation method is through **pip**. Make sure to check if the pip exists in python3 library by checking the pip version.

```shell
$ pip --version
```


## Installation

- To install do

```shell
$ pip install visualmath
```

- For launching **visma** do

```shell
$ visma
```

**NOTE:** For windows user (and those for whom) the above launching option is not available, to launch **visma** GUI do

```shell
$ python
>>> from visma.main import initGUI
>>> initGUI()
```

For other installation methods check out the [install guide](https://github.com/aerospaceresearch/visma/wiki/Install).

## Features:

Currently, VisMa supports:

* **Simplify** -- You can either choose to step by step perform each of the sub-function i.e. addition, subtraction, multiplication and division or choose to simplify the whole expression/equation at once.
* **Find roots** -- You can find roots for a quadratic equation.
* **Factorize** -- You can factorize a given polynomial.
* **Solve** -- This feature will allow you to derive the equation for a variable from a given equation. e.g. from x + y = 1, we can get x = 1 - y or y = 1 - x
* **Integration** -- This feature will allow you to integrate an expression.
* **Differentiation** -- This feature will allow you to differentiate an expression wrt the selected variable.
* **Plot** -- This feature will allow you to get an interactive 2D or 3D graph, with equation of line or plane plotted on it, for better visualisation.


## Using visma

Below is quick-demo of how to use **visma**.

[[/assets/demo.gif]]


## Developer Guide:

For contributing to **visma** refer the [Developer Manual](https://github.com/aerospaceresearch/visma/wiki/Guidelines). If there are any issues or ideas they can be addressed through the [issues](https://github.com/aerospaceresearch/visma/issues) or in [chat room](https://gitter.im/aerospaceresearch/visma).

If **visma** is to be installed for development:

- Download the [source zip](https://github.com/aerospaceresearch/visma/archive/master.zip) and extract.
- For installing dependencies, from source folder do

```shell
$ pip install -r requirements.txt
```

- For launching do

```shell
$ python main.py
```
