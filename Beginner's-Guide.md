This is a brief guide on using visma and for making any contributions to the repo.

**NOTE:** VISualMAth is supported for **python3** and above only.

To build from source:

- [Download](https://github.com/aerospaceresearch/visma/archive/dev.zip) the source code zip
- Extract files
- From project folder, do `$ ./run install` or `$ pip install -r requirements.txt`(make sure to check if the pip exists in python3 library by checking the pip version, use `$ pip --version`)
- To open

If interested in making any contributions to **visma** make sure to go through these steps:

- Clone/fork the dev branch of the repo.
- Before [building from source](https://github.com/aerospaceresearch/visma/wiki/Install#build-from-source) make sure to install all [dependencies](https://github.com/aerospaceresearch/visma/wiki/Dependencies).
- Make necessary changes.
- Before making a PR or commit, run [all modules test](https://github.com/aerospaceresearch/visma/wiki/Tests).
- If all tests pass, make a PR or merge to dev branch.

## Syntax guide

- Follow **_camelCase_** for naming variables, functions etc. For example:
    - variables: _symTokens_, _axisRange_ etc
    - functions: _tokenizer_, _getLevelVariables_ etc
    - classes: _Function_, _SquareMatrix_ etc
- Use 4 spaces for tabs.
- For syntax test refer [this](https://github.com/aerospaceresearch/visma/wiki/Tests#syntax-tests).
