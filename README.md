# Py for Pip
Skeleton for installing a python module from pip.
## Why?
It's good to have a simple known working example.
## What?
This is a simple module which relies on one other module in order to
achieve the dreaded Hello World.

Use at your own caution.
## How?
```
pip install git+https://github.com/drewaogle/py_for_pip.git

python3 -c "
from fancyhello import fancyhello
fancyhello()
"
```

