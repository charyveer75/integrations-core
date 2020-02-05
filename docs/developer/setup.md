# Setup

-----

This will be relatively painless, we promise!

## Python

To work on any integration, you must install Python 3.8+. After installation you must restart your terminal.

### Windows

Windows users have it the easiest. Simply download the latest x86-64 executable installer from https://www.python.org/downloads/windows and run it.
When prompted, be sure to select the option to add to your `PATH`. Also, it is recommended that you choose the per-user installation method.

### macOS

We recommend using [Homebrew](https://brew.sh).

First update the formulae and Homebrew itself:

```
brew update
```

then either install Python:

```
brew install python
```

or upgrade it:

```
brew upgrade python
```

After it completes, check the output to see if it asked you to run any extra commands and if so, execute them.

### Linux

Ah, you enjoy difficult things. Are you using Gentoo?

We recommend using either [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [pyenv](https://github.com/pyenv/pyenv). Whatever you do, never modify the system Python.

## ddev

You will need to install the CLI provided by the package [datadog-checks-dev](ddev/layers.md).
