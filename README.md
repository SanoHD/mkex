# mkex
Python based executable maker

## Installation
    $ sudo mv ~/My/Path/mkex /usr/bin/mkex
    $ sudo chmod +x /usr/bin/mkex

## Using mkex
    $ mkex mycoolprogram.py
This makes mycoolprogram.py a executable, so you can run it from terminal, even without
using .py and the 'python' prefix. It automatically adds a Python 3 shebang. If you are using
Python 2, do `$ mkex -p mycoolprogram.py`. For bash programs, use `-b`. For anything else
use `-c "#! custom-shebang"`
