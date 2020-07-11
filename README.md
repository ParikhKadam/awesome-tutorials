# awesome-tutorials
Tutorials links

## Python

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

### Others
1. Duck Typing - https://realpython.com/lessons/duck-typing/

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

### Comamnds
1. The `tee` command - https://linuxize.com/post/linux-tee-command/
2. The `chsh` command and changing default login shell - https://www.cyberciti.biz/faq/howto-change-linux-unix-freebsd-login-shell
3. The `-` (dash) operator - https://unix.stackexchange.com/questions/16357/usage-of-dash-in-place-of-a-filename 
4. `;` vs. `&&` operator - https://unix.stackexchange.com/questions/37069/what-is-the-difference-between-and-when-chaining-commands
5. The `ln` command and types of links - https://linuxize.com/post/how-to-create-symbolic-links-in-linux-using-the-ln-command/
6. The `find` command - https://www.oracle.com/technical-resources/articles/calish-find.html

### Access control
1. SUID, SGID and Sitcky bits - https://www.howtogeek.com/656646/how-to-use-suid-sgid-and-sticky-bits-on-linux/

### Tricks
1. Use output of a command in output of other command without a pipe `|` - https://stackoverflow.com/questions/4651437/how-do-i-set-a-variable-to-the-output-of-a-command-in-bash

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
4. Git tags basics - https://www.atlassian.com/git/tutorials/inspecting-a-repository/git-tag

## Software Development

### Development Strategies
1. Behaviour Driven Development - https://automationpanda.com/2017/01/25/bdd-101-introducing-bdd/
2. Behaviour Driven Development - https://opensource.com/article/18/5/behavior-driven-python
3. Test Driven Development - http://agiledata.org/essays/tdd.html
4. Test Driven Development vs. Behaviour Driven Development - https://cucumber.io/blog/bdd/bdd-vs-tdd/

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

## Recommender Systems
1. Everything about the basics and terminology - https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada
2. Introduction - https://towardsdatascience.com/recommender-systems-in-practice-cef9033bb23a
