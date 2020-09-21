# Python

Real world python - https://intermediate-and-advanced-software-carpentry.readthedocs.io/en/latest/

https://github.com/ParikhKadam/python-is-cool

https://www.pythonprogramming.in/object-oriented-programming.html

https://www.ics.uci.edu/~brgallar/index.html

Exploring and understanding Python through surprising snippets - https://github.com/satwikkansal/wtfpython

### Regular Expressions
1. Using `re` module -  https://www.delftstack.com/tutorial/python-modules-tutorial/python-regular-expression/

### Magic Methods (Dunder Methods)
1.  Covers highly used magic methods - https://realpython.com/operator-function-overloading/
2. `__repr__` vs. `__str__` and `!r` flag - https://dbader.org/blog/python-repr-vs-str
3. `__format__` and `format()` - https://www.journaldev.com/22821/python-format-function

### Logging
1. Using `logging` module - https://realpython.com/python-logging/

## Decorators
1. Everything - https://realpython.com/primer-on-python-decorators/

### Threading
1. Everything - https://docs.python.org/3/library/threading.html
2. Thread Synchronization - http://effbot.org/zone/thread-synchronization.htm
3. Reader-Writer Lock - https://www.oreilly.com/library/view/python-cookbook/0596001673/ch06s04.html

### Imports
1. `__import__` vs. `import as` and importlib - https://stackoverflow.com/questions/21213355/python-difference-between-import-and-import-as

### `super()`
1. `super()` with wrong arguments - https://stackoverflow.com/questions/18208683/when-calling-super-in-a-derived-class-can-i-pass-in-self-class
2. Understanding of `super()` in deep along with arguments and python2 vs python3 - https://stackoverflow.com/questions/17509846/python-super-arguments-why-not-superobj

### Metaclasses and `type`
1. Dynamically creating classes - https://stackoverflow.com/questions/15247075/how-can-i-dynamically-create-derived-classes-from-a-base-class
2. Everything to need to know about metaclasses - https://realpython.com/python-metaclasses/

### Monkey Patching
1. What is mokey patching - https://stackoverflow.com/questions/5626193/what-is-monkey-patching

### `__dict__`, `dir()` and `vars()`
1. `dir()` and  `__dict__` vs `vars()` - https://stackoverflow.com/questions/980249/difference-between-dir-and-vars-keys-in-python

### Iterables and Iterators, Generators
1. Complete guide - https://dbader.org/blog/python-iterators
2. `__iter__` vs `__next__` (look at the answer given by the author itself) - https://stackoverflow.com/questions/52056146/separating-the-iter-and-next-methods/52056290
3. The use of `__reversed__` - https://stackoverflow.com/questions/27638960/python-reverse-magic-method/27638994#27638994
4. Iterators vs Generators - https://stackoverflow.com/questions/2776829/difference-between-pythons-generators-and-iterators

### `string` library
1. `maketrans()` and `translate()` functions - https://www.tutorialspoint.com/python-maketrans-and-translate-functions

### `contextlib` library
1. `contextlib.contextmanager` and `contextlib.ContextDecorator` (useless) - https://jeffknupp.com/blog/2016/03/07/python-with-context-managers/
2. How `yield` works with `@contextmanager` - https://stackoverflow.com/questions/35489844/what-does-yield-without-value-do-in-context-manager

### PyInstaller
1. How to use pyinstaller - https://www.infoworld.com/article/3543792/how-to-use-pyinstaller-to-create-python-executables.html

### Cython - Python code that can be compiled like C to be used in other C and Python modules
1. Basics - https://pythonprogramming.net/introduction-and-basics-cython-tutorial/

### Encrypting python module
1. The workflow - https://stackoverflow.com/questions/21864682/encrypt-unencrypt-python-scripts-in-c
2. sourcedefender package - https://pypi.org/project/sourcedefender/
3. pyce library - https://github.com/ParikhKadam/awesome-github-repos/blob/master/README.md#pyce
4. pyconcrete library - https://github.com/ParikhKadam/awesome-github-repos/blob/master/README.md#pyconcrete

### CPython - The Python Interpreter
1. Python vs. CPython - https://stackoverflow.com/questions/17130975/python-vs-cpython
2. .pyc, .pyo and .pyd files - https://stackabuse.com/differences-between-pyc-pyd-and-pyo-python-files/

### Mixin
1. What is it and why is it used? - https://stackoverflow.com/questions/533631/what-is-a-mixin-and-why-are-they-useful

### Plug and Play - Modular Systems
1. Implementing a plugin basics - https://alysivji.github.io/simple-plugin-system.html
2. More on loading and running plugins - https://lkubuntu.wordpress.com/2012/10/02/writing-a-python-plugin-api/

### Misc
1. `dict.setdefault()` vs `collection.defaultdict()` -https://stackoverflow.com/questions/3483520/use-cases-for-the-setdefault-dict-method
2. Multiprocessing vs multithreading vs asyncio - https://stackoverflow.com/questions/27435284/multiprocessing-vs-multithreading-vs-asyncio-in-python-3-4/59474824#59474824
3. Type hints, `typing` module - https://stackoverflow.com/questions/32557920/what-are-type-hints-in-python-3-5
4. Variable annotations - https://stackoverflow.com/questions/39971929/what-are-variable-annotations-in-python-3-6

### Testing and Profiling
1. Tools and visualization - https://medium.com/@narenandu/profiling-and-visualization-tools-in-python-89a46f578989
2. Python doctest - https://docs.python.org/3/library/doctest.html
3. Behaviour Driven Development - https://opensource.com/article/18/5/behavior-driven-python
4. unittest - https://www.journaldev.com/15899/python-unittest-unit-test-example
5. `tearDown()` vs. `addCleanup()` in unittest - https://stackoverflow.com/questions/37534021/addcleanup-vs-teardown

### Descriptors
1. The internal logic - https://pabloariasal.github.io/2018/11/25/python-descriptors/
2. Basic - https://deepsource.io/blog/demystifying-python-descriptor-protocol/
3. Understanding the dunder methods - https://stackoverflow.com/questions/3798835/understanding-get-and-set-and-python-descriptors
4. The descriptor protocol - http://martyalchin.com/2007/nov/23/python-descriptors-part-1-of-2/
5. Everything about descriptors - https://web.archive.org/web/20170221220235/http://users.rcn.com/python/download/Descriptor.htm
6. Why descriptors don't work for object attirbutes - https://stackoverflow.com/questions/50556491/why-python-descriptor-work-for-class-level-attribute-and-not-for-an-instance-lev
7. Example use - http://martyalchin.com/2007/nov/24/python-descriptors-part-2-of-2/

### Conda, pip, venv, etc.
1. Conda vs. pip - https://www.anaconda.com/blog/understanding-conda-and-pip
2. Anaconda, conda and pip - https://www.quora.com/What-is-the-comparison-among-conda-vs-pip-vs-anaconda
3. Conda replaces virtualenv - https://stackoverflow.com/questions/34398676/does-conda-replace-the-need-for-virtualenv
4. Pyenv vs. conda - https://bastibe.de/2017-11-20-pyenv.html
5. Using pyenv - https://realpython.com/intro-to-pyenv/

### Building
1. Include non-python files when building the wheel - https://stackoverflow.com/questions/1612733/including-non-python-files-with-setup-py

### Bindings
1. Generate bindings from C++ i.e. call c++ code in python - https://intermediate-and-advanced-software-carpentry.readthedocs.io/en/latest/c++-wrapping.html
2. 2020 guide to the tools used for generating bindings from C and C++ - https://realpython.com/python-bindings-overview/

### Emails
1. Sending emails with `smtplib` and a link to other alternatives - https://realpython.com/python-send-email/#including-html-content

### Others
1. Duck Typing - https://realpython.com/lessons/duck-typing/
2. Some common types of project configuration files - https://martin-thoma.com/configuration-files-in-python/
