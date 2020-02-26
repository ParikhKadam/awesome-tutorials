# awesome-tutorials
Tutorials links

## Python

https://github.com/ParikhKadam/python-is-cool

https://www.pythonprogramming.in/object-oriented-programming.html

### Regular Expressions
1. Using `re` module -  https://www.delftstack.com/tutorial/python-modules-tutorial/python-regular-expression/

### Magic Methods (Dunder Methods)
1.  Covers highly used magic methods - https://realpython.com/operator-function-overloading/
2. `__repr__` vs. `__str__` and `!r` flag - https://dbader.org/blog/python-repr-vs-str

### Logging
1. Using `logging` module - https://realpython.com/python-logging/

### Threading
1. Everything - https://docs.python.org/3/library/threading.html
2. Thread Synchronization - http://effbot.org/zone/thread-synchronization.htm
3. Reader-Writer Lock - https://www.oreilly.com/library/view/python-cookbook/0596001673/ch06s04.html

### Imports
1. `__import__` vs. `import as` and importlib - https://stackoverflow.com/questions/21213355/python-difference-between-import-and-import-as

### App Configuration Files
1. Some common configuration files - https://martin-thoma.com/configuration-files-in-python/

### `super()`
1. `super()` with wrong arguments - https://stackoverflow.com/questions/18208683/when-calling-super-in-a-derived-class-can-i-pass-in-self-class
2. Understanding of `super()` in deep along with arguments and python2 vs python3 - https://stackoverflow.com/questions/17509846/python-super-arguments-why-not-superobj

### Metaclasses and `type`
1. Dynamically creating classes - https://stackoverflow.com/questions/15247075/how-can-i-dynamically-create-derived-classes-from-a-base-class
2. Everything to need to know about metaclasses - https://realpython.com/python-metaclasses/

### `__dict__`, `dir()` and `vars()`
1. `dir()` and  `__dict__` vs `vars()` - https://stackoverflow.com/questions/980249/difference-between-dir-and-vars-keys-in-python

### Iterables and Iterators, Generators
1. Complete guide - https://dbader.org/blog/python-iterators
2. `__iter__` vs `__next__` (look at the answer given by the author itself) - https://stackoverflow.com/questions/52056146/separating-the-iter-and-next-methods/52056290
3. The use of `__reversed__` - https://stackoverflow.com/questions/27638960/python-reverse-magic-method/27638994#27638994
4. Iterators vs Generators - https://stackoverflow.com/questions/2776829/difference-between-pythons-generators-and-iterators

### `string` library
1. `maketrans()` and `translate()` functions - https://www.tutorialspoint.com/python-maketrans-and-translate-functions

### App Package
1. Include non-python files when building the wheel - https://stackoverflow.com/questions/1612733/including-non-python-files-with-setup-py

### Encrypting python module
1. The workflow - https://stackoverflow.com/questions/21864682/encrypt-unencrypt-python-scripts-in-c
2. sourcedefender package - https://pypi.org/project/sourcedefender/
3. pyce library - https://github.com/ParikhKadam/awesome-github-repos/blob/master/README.md#pyce
4. pyconcrete library - https://github.com/ParikhKadam/awesome-github-repos/blob/master/README.md#pyconcrete

## Markdown
1. Collapsable section - https://gist.github.com/pierrejoubert73/902cc94d79424356a8d20be2b382e1ab
2. Everything about the basics of markdown - https://www.markdownguide.org/basic-syntax/
3. Image captions - https://stackoverflow.com/questions/19331362/using-an-image-caption-in-markdown-jekyll

## Devops

### Deployment Strategies
1.  Big-Bang Deployment, Rolling Deployment, Blue-Green (Red-Black or A/B) Deployment - https://dev.to/mostlyjason/intro-to-deployment-strategies-blue-green-canary-and-more-3a3

### Environments
1. Development, Staging and Production - https://dev.to/flippedcoding/difference-between-development-stage-and-production-d0p

## Software Development

### 12-factor app
In the modern era, software is commonly delivered as a service: called web apps, or software-as-a-service. The twelve-factor app is a methodology for building software-as-a-service apps that:

- Use declarative formats for setup automation, to minimize time and cost for new developers joining the project;
- Have a clean contract with the underlying operating system, offering maximum portability between execution environments;
- Are suitable for deployment on modern cloud platforms, obviating the need for servers and systems administration;
- Minimize divergence between development and production, enabling continuous deployment for maximum agility;
- And can scale up without significant changes to tooling, architecture, or development practices.

Includes guide to:
1. Codebase - One codebase tracked in revision control, many deploys
2. Dependencies - Explicitly declare and isolate dependencies
3. Config - Store config in the environment
4. Backing services - Treat backing services as attached resources
5. Build, release, run - Strictly separate build and run stages
6. Processes - Execute the app as one or more stateless processes
7. Port binding - Export services via port binding
8. Concurrency - Scale out via the process model
9. Disposability - Maximize robustness with fast startup and graceful shutdown
10. Dev/prod parity - Keep development, staging, and production as similar as possible
11. Logs - Treat logs as event streams
12. Admin processes - Run admin/management tasks as one-off processes

https://12factor.net

### Software Design Patterns

#### Dependency Injection - Dependency injection is a programming technique that makes a class independent of its dependencies.
1. Dependency Injection with a simple example - https://stackoverflow.com/questions/130794/what-is-dependency-injection
