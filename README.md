# atari_py

[![Build Status](https://travis-ci.org/openai/atari-py.svg?branch=master)](https://travis-ci.org/openai/atari-py)

A packaged and slightly-modified version of [https://github.com/bbitmaster/ale_python_interface](https://github.com/bbitmaster/ale_python_interface).

## Installation

To install via pip, run:

```pip install atari-py```

Alternatively, you can install using setuptools using:

```python setup.py install```

You can also trigger a build of the C++ code via `make`, and then add
this repo to your `PYTHONPATH`:

```export PYTHONPATH=/path/to/atari-py:$PYTHONPATH```

### Install on windows

see [instruction](https://github.com/guozifeng91/atari-py/blob/master/Install%20on%20windows), it needs the repostory from [openai](https://github.com/openai/atari-py) and a modified older version by [rybskej](https://github.com/rybskej/atari-py)

### Common issues

- Make sure you have `cmake` installed. On OSX, you probably want
  `brew install cmake`.
