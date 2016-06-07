## Use python3 and virtual env on Mac Os

Install **python 3** using brew:

    $ brew install python3
Test the **python 3** version installed:

    $ python3 --version
    Python 3.5.1

Using `pyvenv` (instead of `virtualenv`) you will create virtual envirment with **python 3**

    pyvenv venv
Check the **python** version:

    $ source venv/bin/activate
    (venv) $ python
    Python 3.5.1 (default, Apr 18 2016, 11:46:32) 
    [GCC 4.2.1 Compatible Apple LLVM 7.3.0 (clang-703.0.29)] on darwin
    Type "help", "copyright", "credits" or "license" for more information.
    >>>
