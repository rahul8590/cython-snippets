cython-snippets
===============

The repository contains a bunch of Cython Snippets.  This is purely for experimental and learning purposes


Instuctions
-----------

1. Create a setup.py as shown in the sample and execute it.

```
  python setup.py build_ext --inplace.
```

2. The .so file built has all the methods we need to use. Fireup terminal and call the python module 
in hello_world example we can use 
```
  from hello import hel
  hel("bingo!")
  >>>hello bingo #output 
```
