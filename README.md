# octave-cheat-sheet
GNU-Octave cheat sheet

## `syms`
- `pip3 install sympy`
- `>> pkg install -forge symbolic`
- `>> pkg load symbolic`

## TODO
```
Symbolic pkg v2.9.0: Traceback (most recent call last):
  File "<stdin>", line 28, in <module>
AttributeError: '_PrintFunction' object has no attribute '__globals__'
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "<stdin>", line 12, in octoutput_drv
  File "<stdin>", line 54, in octoutput
  File "<stdin>", line 55, in octoutput
AttributeError: module 'sympy' has no attribute 'compatibility'
Closing the Python communications link.

error: Python exception: AttributeError: '_PrintFunction' object has no attribute '__globals__'
    occurred in python_header import block.
    Try "sympref reset" and repeat your command?
    (consider filing an issue at https://github.com/cbm755/octsympy/issues)
error: called from
    pycall_sympy__ at line 191 column 5
    valid_sym_assumptions at line 38 column 10
    assumptions at line 82 column 7
    syms at line 97 column 13
```  
