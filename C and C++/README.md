# C and C++

## C and C++

C - https://gribblelab.org/CBootCamp/

C++ best practices - https://github.com/lefticus/cppbestpractices

Object-oriented programming, analysis, and design - https://www.cs.odu.edu/~zeil/cs330/latest/Directory/outline/index.html

### Datatypes
1. Datatypes in C++ - https://en.cppreference.com/w/cpp/language/types
2. Integer overflow and underflow - https://codingfox.com/3-7-1-formulating-overflow-and-underflow/
3. `size_t` in C++ - https://stackoverflow.com/questions/502856/whats-the-difference-between-size-t-and-int-in-c
4. How to get type of a variable - https://stackoverflow.com/questions/11310898/how-do-i-get-the-type-of-a-variable
5. `typedef` - https://www.cprogramming.com/tutorial/typedef.html
6. When should one use `auto` and when should one not use it? - https://stackoverflow.com/questions/6900459/the-new-keyword-auto-when-should-it-be-used-to-declare-a-variable-type
7. Combined use of `typename` and `typedef` ~without templates~ (typename is only important in templates, see templates section for more info.) - https://stackoverflow.com/questions/11922657/passing-template-typedef-as-argument-to-a-function-template
8. Scope of `typedef` - https://stackoverflow.com/questions/2427739/please-explain-syntax-rules-and-scope-for-typedef
9. Is there any reason not to use fixed width integer types (e.g. uint8_t)? - https://stackoverflow.com/questions/13413521/is-there-any-reason-not-to-use-fixed-width-integer-types-e-g-uint8-t
10. Will a `char` always have 8 bits in C++ - https://stackoverflow.com/questions/9727465/will-a-char-always-always-always-have-8-bits
11. `typedef` vs. `using` (C++11) and alias templates - https://www.internalpointers.com/post/differences-between-using-and-typedef-modern-c
12. `size_t` vs. `ssize_t` - https://stackoverflow.com/questions/15739490/should-use-size-t-or-ssize-t

### Type casting
1. All the methods available for casting and their uses - https://stackoverflow.com/questions/332030/when-should-static-cast-dynamic-cast-const-cast-and-reinterpret-cast-be-used
2. Available ways to cast type and when to use which - https://www.bogotobogo.com/cplusplus/typecast.php
3. How to use `const_cast`? - https://stackoverflow.com/questions/19554841/how-to-use-const-cast

### Structs and Unions
1. Bitfields - https://stackoverflow.com/questions/31850314/colon-used-in-variable-initialization
1. When and how to use bitfields - https://stackoverflow.com/questions/4240974/when-is-it-worthwhile-to-use-bit-fields

### Classes, Functions, Objects, etc.. (C++)
1. Everything about inline functions - https://stackoverflow.com/questions/1759300/when-should-i-write-the-keyword-inline-for-a-function-method
2. Lambda fuctions - https://stackoverflow.com/questions/7627098/what-is-a-lambda-expression-in-c11
3. Different ways of returning multiple values from function - https://stackoverflow.com/questions/321068/returning-multiple-values-from-a-c-function
4. Comparision of `std::tuple` vs. pass by reference for returning multiple values - https://stackoverflow.com/questions/47790909/which-is-better-returning-tuple-or-passing-arguments-to-function-as-references/61186156#61186156
5. A simplistic tutorial on ADTs in C++ - https://www.cs.odu.edu/~zeil/cs330/latest/Public/implementingADTS/index.html
6. How does the compiler calculate size of object in C++ - https://stackoverflow.com/questions/937773/how-do-you-determine-the-size-of-an-object-in-c
7. Lambda expression complete reference - https://en.cppreference.com/w/cpp/language/lambda

### Enum
1. `enum` vs `enum class`  -https://stackoverflow.com/questions/18335861/why-is-enum-class-preferred-over-plain-enum
2. Define enum's underlying type (don't confuse it with inheritance) - https://stackoverflow.com/questions/35294575/enum-inheriting-from-primitive-type
3. `enum class` is not a class - https://stackoverflow.com/questions/21295935/can-a-c-enum-class-have-methods
4. Complete understanding with enum initialization - https://en.cppreference.com/w/cpp/language/enum

### Plain Old Data
1. Simplistic definition - https://stackoverflow.com/questions/146452/what-are-pod-types-in-c
2. PODs and Aggregates - https://stackoverflow.com/questions/5442717/cant-c-pod-type-have-any-constructor

### Object Lifecycle
1. Initialization and Declaration, Lifecycle, RAII - https://stackoverflow.com/questions/3506818/object-is-already-initialized-on-declaration
2. Define specific scope - https://stackoverflow.com/questions/14620898/how-does-one-declare-a-variable-inside-an-if-statement
3. Data members are initialized before constructor body code runs - https://www.quora.com/In-C++-why-are-class-members-initialized-with-their-default-constructor-before-the-constructor-body-executes-instead-of-the-compiler-detecting-which-members-werent-initialized-during-the-constructor-and-initializing-them-with-the-default-constructor-afterwards
4. Delegating constructors - https://thenewcpp.wordpress.com/2013/07/25/delegating-constructors/

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
6. Pointer vs. Reference as return types - https://stackoverflow.com/questions/7813728/pointer-vs-reference-return-types
7. Passing integers via pointer/reference vs. copying - https://stackoverflow.com/questions/3009543/passing-integers-as-constant-references-versus-copying
8. Return Value Optimization - https://stackoverflow.com/questions/4643713/c-returning-reference-to-local-variable
9. Pointer vs. Reference as data member - https://stackoverflow.com/questions/892133/should-i-prefer-pointers-or-references-in-member-data

### Reference of Reference (rvalue reference)
1. Basics of Reference vs. reference of reference, temporary objects, ownership transfer, speed advantage, `std::move()`, forwarding reference and `std::forward()` in templates - https://www.fluentcpp.com/2018/02/06/understanding-lvalues-rvalues-and-their-references/
2. Better understanding of lvalue and rvalue, rvalue reference, move semantics and rule of three/five - https://www.internalpointers.com/post/c-rvalue-references-and-move-semantics-beginners

### Iterators (C++)
1. What and Why- https://users.cs.northwestern.edu/~riesbeck/programming/c++/stl-iterators.html
2. Writing iterators for custom container - https://users.cs.northwestern.edu/~riesbeck/programming/c++/stl-iterator-define.html

### Smart Pointers (C++)
1. Performance overhead - https://stackoverflow.com/questions/22295665/how-much-is-the-overhead-of-smart-pointers-compared-to-normal-pointers-in-c
2. Memory and Performance overhead - https://www.modernescpp.com/index.php/memory-and-performance-overhead-of-smart-pointer
3. `shared_ptr` for arrays? - https://stackoverflow.com/questions/3266443/can-you-use-a-shared-ptr-for-raii-of-c-style-arrays

### `const` and `static` keywords
1. Everything about `const` - https://www.studytonight.com/cpp/const-keyword.php
2. Why can a const member function modify a static data member? - https://stackoverflow.com/questions/43936404/why-can-a-const-member-function-modify-a-static-data-member
3. What is the meaning of a const at end of a member function? - https://stackoverflow.com/questions/4059932/what-is-the-meaning-of-a-const-at-end-of-a-member-function
4. What kind of optimization can `const` offer? - https://stackoverflow.com/questions/27466642/what-kind-of-optimization-does-const-offer-in-c-c
5. Static method can be called using class member access syntax (apart from calling it with static member access syntax) - https://stackoverflow.com/questions/46544292/c-calling-a-static-method
6. Static members should not be initialized in header files - https://stackoverflow.com/questions/18860895/how-to-initialize-static-members-in-the-header
7. Code should always be written in code files and not header, even if it is static funciton - https://stackoverflow.com/questions/780730/c-c-static-function-in-header-file-what-does-it-mean
8. Global static variables vs. Class static variables - https://stackoverflow.com/questions/3698043/static-variables-in-c

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
11. Vector deallocation - https://stackoverflow.com/questions/3054567/right-way-to-deallocate-an-stdvector-object
12. `std::array`vs. `std::vector` in terms of performance - https://github.com/isocpp/CppCoreGuidelines/issues/493

### String
1. `char*` vs. `std::string` - https://stackoverflow.com/questions/1764079/why-do-you-prefer-char-instead-of-string-in-c
2. `char*` vs. `std::string` in memory management and `\0` character - https://stackoverflow.com/questions/1287306/difference-between-string-and-char-types-in-c
3. `std::string` automatic resizing doubling algorithm - https://stackoverflow.com/questions/3557591/stdstring-and-its-automatic-memory-resizing
4. Clear a stringstream variable - https://stackoverflow.com/questions/20731/how-do-you-clear-a-stringstream-variable
5. `string` vs `stringstream` - https://stackoverflow.com/questions/19844858/c-stdostringstream-vs-stdstringappend
6. `c_str()` - https://stackoverflow.com/questions/7416445/what-is-use-of-c-str-function-in-c

### File IO
1. Difference between `operator <<` and `write()` - https://stackoverflow.com/questions/4329835/whats-the-difference-between-ofstream-and-write
2. High performance reading and writing - https://stackoverflow.com/questions/38646062/c-high-performance-file-reading-and-writing-c14
3. Read and write files directly using system calls to have total control - https://stackoverflow.com/questions/14003466/how-can-i-read-and-write-from-files-using-the-headers-fcntl-h-and-unistd-h
4. Read and write files directly using system calls to have total control - https://www.geeksforgeeks.org/input-output-system-calls-c-create-open-close-read-write/
5. Difference in file system call functions between windows and POSIX - https://stackoverflow.com/questions/36438732/close-vs-close-read-vs-read-write-vs-write-what-is-difference
6. `fcntl.h` and `unistd.h` in POSIX (Linux and MAC) vs `io.h` in windows - https://stackoverflow.com/questions/49001326/convert-the-linux-open-read-write-close-functions-to-work-on-windows
7. `mmap` unix tutorial - https://www.linuxquestions.org/questions/programming-9/mmap-tutorial-c-c-511265/

### Templates
1. Complete guide - https://www.bogotobogo.com/cplusplus/templates.php
2. `typename` - https://stackoverflow.com/questions/1600936/officially-what-is-typename-for
3. `typename` vs. `class` - https://stackoverflow.com/questions/2023977/difference-of-keywords-typename-and-class-in-templates
4. Instatiation vs. Specialization - https://stackoverflow.com/questions/3914642/difference-between-instantiation-and-specialization-in-c-templates
5. `using` and alias templates - https://www.internalpointers.com/post/differences-between-using-and-typedef-modern-c
6. Variadic templates - https://eli.thegreenplace.net/2014/variadic-templates-in-c/
7. Variadic templates (easy guide) -  https://kevinushey.github.io/blog/2016/01/27/introduction-to-c++-variadic-templates/

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
11. How does the compiler calculate size of object in C++ - https://stackoverflow.com/questions/937773/how-do-you-determine-the-size-of-an-object-in-c

### Data conversion
1. Bytes to integer - https://stackoverflow.com/questions/34943835/convert-four-bytes-to-integer-using-c/34944089
2. Convert any object to/from bytes - http://www.cplusplus.com/forum/beginner/155821/

### MACROS
1. Conditional Compilation - https://www.cs.auckland.ac.nz/references/unix/digital/AQTLTBTE/DOCU_078.HTM
2. `#if` vs. `#ifdef` vs. `#if defined` - https://stackoverflow.com/questions/39290019/is-if-defined-macro-equivalent-to-ifdef-macro

### Build and Install (Executables, Libraries, Object Files, etc.)
1. Difference between object files and executables - https://stackoverflow.com/questions/25896207/difference-between-code-object-and-executable-file

### Tricks
1. Determine OS using preprocessor directives - https://stackoverflow.com/questions/5919996/how-to-detect-reliably-mac-os-x-ios-linux-windows-in-c-preprocessor
2. Various available preprocessor directives in different OS - https://stackoverflow.com/questions/142508/how-do-i-check-os-with-a-preprocessor-directive
3. Use `++i` instead of `i++` where possible - https://stackoverflow.com/questions/24901/is-there-a-performance-difference-between-i-and-i-in-c
4. Compile windows code on ubuntu using mingw - http://www.mingw.org/
5. Compile linux code on windows using cygwin - https://cygwin.com/

## CMake

### Introduction
1. Basic usage - https://mirkokiefer.com/cmake-by-example-f95eb47d45b1
2. Intermediate usage - https://www.siliceum.com/en/blog/post/cmake_01_cmake-basics
3. The most complete CMake guide (includes static and shared libraries, and much more.. please follow the sequence) - https://medium.com/@onur.dundar1/cmake-tutorial-585dd180109b

### How?
1. How does `add_executable()` identify which is the main file (entry point) out of a list of files passed to it - https://answers.ros.org/question/244489/multiple-files-in-one-add_executable/ 

### Tricks
1. How to set OS specific instructions - https://stackoverflow.com/questions/9160335/os-specific-instructions-in-cmake-how-to

