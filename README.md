# HNRWS2015 Textnetworks

This is the repository for the Textnetworks session at the Historical Network Research workshop 2015.

## Installation

For creating textnetworks, we will use [TCFnetworks](https://github.com/SeNeReKo/TCFnetworks). It depends on [TCFlib](https://github.com/SeNeReKo/TCFlib) and [python-igraph](http://igraph.org/python/).

### On Windows

#### 1. Install Anaconda

1. Go to [http://continuum.io/downloads](http://continuum.io/downloads).
2. Click “I want Python 3.4.”
3. Click the download button: “Your Operating System — Python 3.4.”
4. Follow the installation instructions.

#### 2. Install python-igraph

There are packages ready for igraph on Windows. igraph requires another package, pycairo.

1. Go to the [pycairo packages](http://www.lfd.uci.edu/~gohlke/pythonlibs/#pycairo) and download the package for your python version (3.4) and windows version (32 or 64, you can find that out through the “PC Information” window in Windows). Save it to your “Downloads” folder.
2. Also download the [igraph package](http://www.lfd.uci.edu/~gohlke/pythonlibs/#python-igraph).
3. Open the “Anaconda Command Prompt” application (you find it in the windows application list by searching for “anaconda”)
4. Enter the following commands. The package names should match your version of the package, but it is usually enough to enter the first part of the file and press the Tab button to automatically complete the file name.

        pip install pycairo<version>.whl
        pip install python_igraph<version>.whl

#### 3. Install tcflib and tcfnetworks

In the “Anaconda Command Prompt,” print the following commands:

    pip install tcflib
    pip install tcfnetworks

### On MacOS and Linux

You can also use Anaconda and install python-igraph, tcflib and tcfnetworks through pip. On MacOS, you might want to follow these [instructions](https://victorfang.wordpress.com/2014/08/14/python-igraph-installed-on-anaconda-mac-osx-10-8-successfully/) to successfully build igraph.
