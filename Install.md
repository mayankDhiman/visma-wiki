**NOTE:** VISualMAth is supported for **python3** and above only. The recommended installation method is through **pip**. Make sure to check if the pip exists in python3 library by checking the pip version.

```shell
$ pip --version
```

To install visma the below three methods can be used. If installing visma for development go with the last method.

## Installing using pip

To install the latest version visma do

```shell
$ pip install visualmath
```

That's all !

## Download builds

The files in the [releases section](https://github.com/aerospaceresearch/visma/releases) can also be used to install visma. Download any one of the files named:

- VISualMAth-x.y.z-py3-none-any.whl
- VISualMAth-x.y.z.tar.gz

Use pip to install the files
```shell
$ pip install VISualMAth-x.y.z-py3-none-any.whl
```
 or

```shell
$ pip install VISualMAth-x.y.z.tar.gz
```

## Build from source

**NOTE**: If developing visma this method is recommended.

 [Download](https://github.com/aerospaceresearch/visma/archive/master.zip) the source code zip

Extract files.

From project folder do


```shell
$ pip install -r requirements.txt
```

or

```shell
$ ./run install
```

Check out the [Start guide](https://github.com/aerospaceresearch/visma/wiki/Start).
