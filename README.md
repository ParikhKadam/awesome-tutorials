# awesome-tutorials
Tutorials links

## Python

https://github.com/ParikhKadam/python-is-cool

https://www.pythonprogramming.in/object-oriented-programming.html

https://www.ics.uci.edu/~brgallar/index.html

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

### Tricks
1. `dict.setdefault()` vs `collection.defaultdict()` -https://stackoverflow.com/questions/3483520/use-cases-for-the-setdefault-dict-method

### Profiling
1. Tools and visualization - https://medium.com/@narenandu/profiling-and-visualization-tools-in-python-89a46f578989

## C and C++

C - https://gribblelab.org/CBootCamp/

C++ best practices - https://github.com/lefticus/cppbestpractices

Object-oriented programming, analysis, and design - https://www.cs.odu.edu/~zeil/cs330/latest/Directory/outline/index.html

### Datatypes
1. Datatypes in C++- https://codingfox.com/3-7-data-types-putting-all-together/
2. Integer overflow and underflow - https://codingfox.com/3-7-1-formulating-overflow-and-underflow/
3. `size_t` in C++ - https://stackoverflow.com/questions/502856/whats-the-difference-between-size-t-and-int-in-c
4. How to get type of a variable - https://stackoverflow.com/questions/11310898/how-do-i-get-the-type-of-a-variable
5. `typedef` - https://www.cprogramming.com/tutorial/typedef.html

### Classes, Functions, Objects, etc.. (C++)
1. Everything about inline functions - https://stackoverflow.com/questions/1759300/when-should-i-write-the-keyword-inline-for-a-function-method
2. Lambda fuctions - https://stackoverflow.com/questions/7627098/what-is-a-lambda-expression-in-c11

### Plain Old Data
1. Simplistic definition - https://stackoverflow.com/questions/146452/what-are-pod-types-in-c
2. PODs and Aggregates - https://stackoverflow.com/questions/5442717/cant-c-pod-type-have-any-constructor

### Object Lifecycle
1. Initialization and Declaration, Lifecycle, RAII - https://stackoverflow.com/questions/3506818/object-is-already-initialized-on-declaration
2. Define specific scope - https://stackoverflow.com/questions/14620898/how-does-one-declare-a-variable-inside-an-if-statement
3. Data members are initialized before constructor body code runs - https://www.quora.com/In-C++-why-are-class-members-initialized-with-their-default-constructor-before-the-constructor-body-executes-instead-of-the-compiler-detecting-which-members-werent-initialized-during-the-constructor-and-initializing-them-with-the-default-constructor-afterwards

### Inheritance
1. Covariant return types - https://stackoverflow.com/questions/1882584/what-is-a-covariant-return-type

### Initializer list
1. Everything - https://www.studytonight.com/cpp/initializer-list-in-cpp.php
2. Why initializer lists give speed boost? - https://stackoverflow.com/questions/9903248/initializing-fields-in-constructor-initializer-list-vs-constructor-body/9903262#9903262

### References and Pointers
1. References vs. pointers simple differences - https://www.quora.com/What-are-the-advantages-of-references-over-pointers-and-vice-versa-in-C++
2. References vs. Pointers deeper understanding - https://www.embedded.com/references-vs-pointers/
3. What is `void` pointer? - https://stackoverflow.com/questions/8530080/what-is-a-void-pointer-in-c
4. Limitations of ``void` pointer - https://stackoverflow.com/questions/32489899/usage-of-void-pointers-in-c
5. When to use `void` pointers - https://stackoverflow.com/questions/1025579/when-to-use-a-void-pointer

## Iterators (C++)
1. What and Why- https://users.cs.northwestern.edu/~riesbeck/programming/c++/stl-iterators.html
2. Writing iterators for custom container - https://users.cs.northwestern.edu/~riesbeck/programming/c++/stl-iterator-define.html

### Smart Pointers (C++)
1. Performance overhead - https://stackoverflow.com/questions/22295665/how-much-is-the-overhead-of-smart-pointers-compared-to-normal-pointers-in-c
2. Memory and Performance overhead - https://www.modernescpp.com/index.php/memory-and-performance-overhead-of-smart-pointer
3. `shared_ptr` for arrays? - https://stackoverflow.com/questions/3266443/can-you-use-a-shared-ptr-for-raii-of-c-style-arrays

### `const` and `static` keywords
1. Everything about `const` - https://www.studytonight.com/cpp/const-keyword.php
2. Why can a const member function modify a static data member? - https://stackoverflow.com/questions/43936404/why-can-a-const-member-function-modify-a-static-data-member

### Array
1. `std::array` vs. `std::vector` in C++ - https://stackoverflow.com/questions/15079057/arrays-vs-vectors-introductory-similarities-and-differences
2. Array - https://www.cpp.edu/~elab/ECE114/Array.html
3. `std::vector` in C++ - https://www.codesdope.com/cpp-stdvector/
4. `std::vector` in C++ - https://www.bitdegree.org/learn/c-plus-plus-vector
5. `std::array` vs static array vs `std::vector` - https://stackoverflow.com/questions/18868860/c11-stdarray-vs-static-array-vs-stdvector
6. `shared_ptr` for arrays? - https://stackoverflow.com/questions/3266443/can-you-use-a-shared-ptr-for-raii-of-c-style-arrays
7. Difference between array type and array allocated with malloc - https://stackoverflow.com/questions/10575544/difference-between-array-type-and-array-allocated-with-malloc
8. Different ways of passing array to functions - https://stackoverflow.com/questions/14309136/passing-arrays-to-function-in-c
9. Pssing array to functions - https://softwareengineering.stackexchange.com/questions/269648/int-vs-int-n-vs-int-n-in-functions-parameters-which-one-do-you-think-i/269721#269721?newreg=3361119f1a4a4a8c8d00a7060f3fac36
10. Size of vector in C++ - https://stackoverflow.com/questions/34024805/c-sizeof-vector-is-24

### Templates
1. Complete guide - https://www.bogotobogo.com/cplusplus/templates.php
2. `typename` - https://stackoverflow.com/questions/1600936/officially-what-is-typename-for
3. `typename` vs. `class` - https://stackoverflow.com/questions/2023977/difference-of-keywords-typename-and-class-in-templates
4. Instatiation vs. Specialization - https://stackoverflow.com/questions/3914642/difference-between-instantiation-and-specialization-in-c-templates

### StringStream
1. Clear a stringstream variable - https://stackoverflow.com/questions/20731/how-do-you-clear-a-stringstream-variable

### Profiling and Detecting memory leaks
1. Valgrind (callgrind) and Kcachegrind - https://codeyarns.com/2013/09/17/how-to-profile-cc-code-using-valgrind-and-kcachegrind/
2. Valgrind tutorial - http://pages.cs.wisc.edu/~bart/537/valgrind.html

### Memory allocation
1. Stack vs. Heap - https://gribblelab.org/CBootCamp/7_Memory_Stack_vs_Heap.html
2. Memory allocation strategies - https://barrgroup.com/embedded-systems/how-to/malloc-free-dynamic-memory-allocation
3. Memory fragmentation solution - https://stackoverflow.com/questions/60871/how-to-solve-memory-fragmentation
4. Pros and Cons of the various Memory Allocation Strategies - https://www.modernescpp.com/index.php/pros-and-cons-of-the-various-memory-management-strategies
5. How is an object stored in heap - https://stackoverflow.com/questions/22388079/how-is-an-object-stored-in-heap
6. Memory pool -https://stackoverflow.com/questions/6747959/questions-about-memory-pool
7. Basic implementation of memory pool - https://www.codeproject.com/Articles/27487/Why-to-use-memory-pool-and-how-to-implement-it
8. Complete implementation of memory pool - https://www.codeproject.com/Articles/15527/C-Memory-Pool
9. `VirtualAlloc()` vs. `HeapAlloc()` vs. `malloc()` vs. `new()` - https://stackoverflow.com/questions/872072/whats-the-differences-between-virtualalloc-and-heapalloc
10. Memory allocation in terms of virtual memory - https://stackoverflow.com/questions/3954188/how-malloc-works
11. `malloc()` vs. `calloc()` vs. `new()` in C++ - https://stackoverflow.com/questions/807939/what-is-the-difference-between-new-and-malloc-and-calloc-in-c
12. Writing a Memory Pool Allocator - http://dmitrysoshnikov.com/compilers/writing-a-pool-allocator/
13. Various types of memory managers, their implementation and advantages/disadvantages - https://developer.ibm.com/technologies/systems/tutorials/au-memorymanager/
14. Concept of automatic storage - https://stackoverflow.com/questions/10157122/object-creation-on-the-stack-heap

### Data conversion
1. Bytes to integer - https://stackoverflow.com/questions/34943835/convert-four-bytes-to-integer-using-c/34944089

## CMake

### `add_executable()`
1. How does `add_executable()` identify which is the main file (entry point) out of a list of files passed to it - https://answers.ros.org/question/244489/multiple-files-in-one-add_executable/ 

## OpenCV

### Affine Transforms
1. Rotate an image - https://stackoverflow.com/questions/9041681/opencv-python-rotate-image-by-x-degrees-around-specific-point

## Pandas

### Filter
1. Filter dataframe based on row index - https://stackoverflow.com/questions/53482760/filter-data-frame-based-on-index-value-in-python/53482813
2. `loc()` vs `iloc()` - https://www.pythonprogramming.in/what-is-difference-between-iloc-and-loc-in-pandas.html
3. Select rows/columns based on regex - https://stackoverflow.com/questions/30808430/how-to-select-columns-from-dataframe-by-regex
4. Select rows based on a column whose value lies between two values - https://stackoverflow.com/questions/31617845/how-to-select-rows-in-a-dataframe-between-two-values-in-python-pandas/40442778

### Operations
1. `and` vs. `&` - https://stackoverflow.com/questions/54315627/difference-between-and-and-in-pandas
2. Delete rows and columns - https://chrisalbon.com/python/data_wrangling/pandas_dropping_column_and_rows/
3. Adding a new row using loc - https://stackoverflow.com/questions/10715965/add-one-row-to-pandas-dataframe

## Angular - The angular framework (not angularjs)

### Event Binding
1. Core concept - https://www.pluralsight.com/guides/angular-event-binding

### @Input and @Output
1. Core concept - https://blog.hackages.io/angular-component-interaction-with-input-output-and-eventemitter-72526422b95c
2. Core concept - https://medium.com/@foolishneo/understanding-input-output-and-eventemitter-in-angular-c1aeb9fff594

### Event Emmiters
1. Everything you need to know - https://netbasal.com/event-emitters-in-angular-13e84ee8d28c

### Event Bubbling
1. Everything you need to know - https://www.radzen.com/blog/angular-event-bubbling/

### ng-template Directive
1. Everything you need to know - https://www.angularjswiki.com/angular/what-is-ng-template-in-angular/#using-ng-template-with-ngfor-example

### Component Lifecycle
1. https://angular.io/guide/lifecycle-hooks

### ngClass and ngStyle
1. https://blog.angular-university.io/angular-ngclass-ngstyle/

## Markdown
1. Collapsable section - https://gist.github.com/pierrejoubert73/902cc94d79424356a8d20be2b382e1ab
2. Everything about the basics of markdown - https://www.markdownguide.org/basic-syntax/
3. Image captions - https://stackoverflow.com/questions/19331362/using-an-image-caption-in-markdown-jekyll

## Linux

### User management
1. Enable/Disable user (Expire account, lock login using passowrd, expire password) - https://askubuntu.com/questions/282806/how-to-enable-or-disable-a-user
2. Switch betwwen users on terminal using `su` and `sudo` - https://unix.stackexchange.com/questions/3568/how-to-switch-between-users-on-one-terminal
3. User creation using `useradd` - https://linuxize.com/post/how-to-create-users-in-linux-using-the-useradd-command/
4. Renaming users - https://linuxtechlab.com/rename-user-in-linux-rename-home-directory/
5. `/etc/shadow` - https://unix.stackexchange.com/questions/252016/difference-between-vs-vs-in-etc-shadow
6. `/etc/passwd` vs. `/etc/shadow` - https://askubuntu.com/questions/445361/what-is-difference-between-etc-shadow-and-etc-passwd

### Cron jobs
1. Create cron job using terminal - https://stackoverflow.com/questions/4880290/how-do-i-create-a-crontab-through-a-script
2. Manually adding cron jobs - https://www.cyberciti.biz/faq/how-do-i-add-jobs-to-cron-under-linux-or-unix-oses/

### `nohup` - Run process in background without binding it to a terminal
1. Basics - https://www.journaldev.com/27875/nohup-command-in-linux
2. Killing a `nohup` process - https://stackoverflow.com/questions/17385794/how-to-get-the-process-id-to-kill-a-nohup-process

## Devops

### Deployment Strategies
1.  Big-Bang Deployment, Rolling Deployment, Blue-Green (Red-Black or A/B) Deployment - https://dev.to/mostlyjason/intro-to-deployment-strategies-blue-green-canary-and-more-3a3

### Environments
1. Development, Staging and Production - https://dev.to/flippedcoding/difference-between-development-stage-and-production-d0p

## Vagrant
1. Change the way vagrant ssh login works, use your own key for ssh - http://ermaker.github.io/blog/2015/11/18/change-insecure-key-to-my-own-key-on-vagrant.html

## Git
1. Initializing a local folder as git repo and pushing it online - https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line
2. Push a local branch to remote - https://www.freecodecamp.org/forum/t/push-a-new-local-branch-to-a-remote-git-repository-and-track-it-too/13222
3. Reverting back to specific commit - https://stackoverflow.com/questions/3489173/how-to-clone-git-repository-with-specific-revision-changeset

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

### Composition and Inheritance
1. Composition vs. Inheritance - https://www.thoughtworks.com/de/insights/blog/composition-vs-inheritance-how-choose

## Reverse Engineering
1. Tools for .so (shared object) files - https://reverseengineering.stackexchange.com/questions/4624/how-do-i-reverse-engineer-so-files-found-in-android-apks?newreg=c5fdcf661f3d401d944b066853af1d10

## Cryptography
1. Why `xor` encryption - https://stackoverflow.com/questions/1379952/why-is-xor-used-in-cryptography

## Encoding
1. `hexadecimal` and `base64` encoding of a windows executable - https://stackoverflow.com/questions/36796744/convert-exe-to-hex-to-be-run-by-python

## Recommender Systems
1. Everything about the basics and terminology - https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada
2. Introduction - https://towardsdatascience.com/recommender-systems-in-practice-cef9033bb23a
