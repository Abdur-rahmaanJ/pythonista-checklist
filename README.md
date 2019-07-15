# pythonista-checklist
What you **need** to be a Pro Python Programmer

Also taken into consideration for Topics section: freelancer.com projects analysis and codementor.io freelancer interviewer guides.

Freelancing requires some tough skills, beyond casual programming. This checklist aims at helping with skilling-up.

This list is exhausive but relevent, some sections are detailed, some not. Only one who wishes mastery would find it a boon (else who would want to learn it all?)

A Python expert is defined as such:
- Mastered basics
- Mastered Std lib
- Mastered popular frameworks
- Mastered algorithms
- Mastered CPython C Api
- Mastered basic devops like aws deloyment, tests and continuos deployment
- Have real-life experiences

The first 3 is enough to make you a Python Trainer, and enough to take projects. That's what this checklist aims for.

[... in progress] 

## Practical Use**
Keep a copy of the readme and check the list as you go. But keep those in mind:

- You won't complete it overnight.
- Don't wait to complete it to start freelancing.
- You skill up by doing.
- Learning frameworks is as important as learning a lanuguage.

The Standard Library section for example is long and should be continuosly tackled

# Index

- Core
- Std Lib
- Fundamental 3rd Party
- Topics
- Time Management
- Project Management
- Portfolio
- Finding Clients

# Core

## Complete Beginner
**Declaration of variables**
- [ ] multiple declaration

**Data structures _and_ manipulation:**
- [ ] list
- [ ] tuple
- [ ] dictionary
- [ ] set

**Input**
- [ ] ask user input via input()

**Print**
- [ ] print parameters: elements, sep, end, file, flush
- [ ] redirection to std output

**Math Operations**
- +, -, /, //, *, **

**Booleans**
- [ ] know that True equals 1
- [ ] check booleans using bool()

**Conditionals**
- [ ] if, elif, else
- [ ] and, or

**Unpacking**
- use of ```*``` in unpacking

**Loop**
- [ ] range: element, start, index
- [ ] for loop to iterate over elements, use of enumerate
- [ ] else use in for loop
- [ ] while loop

**Inspection**
- [ ] help()
- [ ] dir()
- [ ] type()
- [ ] id()

**String manipulation**
- [ ] normal string methods: 
```
capitalize, casefold, center, count, encode, endswith, expandtabs, find, format, 
format_map, index, isalnum, isalpha, isascii, isdecimal, isdigit, isidentifier, 
islower, isnumeric, isprintable, isspace, istitle, isupper, join, ljust, lower, 
lstrip, maketrans, partition, replace, rfind, rindex, rjust, rpartition, rsplit, 
rstrip, split, splitlines, startswith, strip, swapcase, title, translate, upper, zfill
```


**References and copy**
- .copy(), .deepcopy() and references
- references within functions

**iterators and generators**
- [ ] iterator
- [ ] generators and the yield keyword

**Functions**
- [ ] declaration
- [ ] functions in functions
- [ ] decorators
- [ ] args, kwargs

**Comprehensions**
- [ ] list, dictionary and generator comprehensions
- [ ] if, else in generators
- [ ] nested list comprehensions

**OOP**
- [ ] know that objects inherit from the object class
- [ ] constructor and without constructor
- [ ] methods
- [ ] instantiation
- [ ] dataclass and associated built-ins viz classmethod, staticmethod, property
- [ ] inheritance
- [ ] ```__slot__```

**Other built-ins**
- [ ] **normal:** 
```abs, all, any, ascii, bin, breakpoint, bytearray, bytes, callable, 
chr, compile, complex, copyright, credits, delattr, dict, divmod, 
enumerate, eval, exec, exit, filter, float, format, frozenset, getattr, globals, 
hasattr, hash, hex, int, isinstance, issubclass, iter, len, license, 
list, locals, map, max, memoryview, min, next, object, oct, open, ord, pow, 
quit, repr, reversed, round, set, setattr, slice, sorted, 
str, sum, super, tuple, vars, zip
```

- [ ] **exceptions**: 
```ArithmeticError, AssertionError, AttributeError, BaseException, BlockingIOError, BrokenPipeError, 
BufferError, BytesWarning, ChildProcessError, ConnectionAbortedError, ConnectionError, 
ConnectionRefusedError, ConnectionResetError, DeprecationWarning, EOFError, Ellipsis, EnvironmentError, 
Exception, False, FileExistsError, FileNotFoundError, FloatingPointError, FutureWarning, GeneratorExit, 
IOError, ImportError, ImportWarning, IndentationError, IndexError, InterruptedError, IsADirectoryError,
KeyError, KeyboardInterrupt, LookupError, MemoryError, ModuleNotFoundError, NameError, None, 
NotADirectoryError, NotImplemented, NotImplementedError, OSError, OverflowError, PendingDeprecationWarning, 
PermissionError, ProcessLookupError, RecursionError, ReferenceError, ResourceWarning, RuntimeError, 
RuntimeWarning, StopAsyncIteration, StopIteration, SyntaxError, SyntaxWarning, SystemError, SystemExit, 
TabError, TimeoutError, True, TypeError, UnboundLocalError, UnicodeDecodeError, UnicodeEncodeError, 
UnicodeError, UnicodeTranslateError, UnicodeWarning, UserWarning, ValueError, Warning, WindowsError, 
ZeroDivisionError
```

**Lambdas**
- [ ] assigned to variables
- [ ] without arg, with arg, with muliple arguments
- [ ] keywords with lambdas

**Object and Module Attributes**
- [ ] **by default:**  
```
__class__, __delattr__, __dir__, __doc__, __eq__, __format__, __ge__, __getattribute__, 
__gt__, __hash__, __init__, __init_subclass__, __le__, __lt__, __ne__,
__new__, __reduce__, __reduce_ex__, __repr__, __setattr__, __sizeof__, __str__,
__subclasshook__
```
- [ ] TODO: add more

**Async**
- [ ] TODO: add more

# Standard Library

Learn all these:

**Text Processing Services**

- [ ] string — Common string operations
- [ ] re — Regular expression operations
- [ ] difflib — Helpers for computing deltas
- [ ] textwrap — Text wrapping and filling
- [ ] unicodedata — Unicode Database
- [ ] stringprep — Internet String Preparation
- [ ] readline — GNU readline interface
- [ ] rlcompleter — Completion function for GNU readline

**Binary Data Services**

- [ ] struct — Interpret bytes as packed binary data
- [ ] codecs — Codec registry and base classes

**Data Types**

- [ ] datetime — Basic date and time types
- [ ] calendar — General calendar-related functions
- [ ] collections — Container datatypes
- [ ] collections.abc — Abstract Base Classes for Containers
- [ ] heapq — Heap queue algorithm
- [ ] bisect — Array bisection algorithm
- [ ] array — Efficient arrays of numeric values
- [ ] weakref — Weak references
- [ ] types — Dynamic type creation and names for built-in types
- [ ] copy — Shallow and deep copy operations
- [ ] pprint — Data pretty printer
- [ ] reprlib — Alternate repr() implementation
- [ ] enum — Support for enumerations

**Numeric and Mathematical Modules**

- [ ] numbers — Numeric abstract base classes
- [ ] math — Mathematical functions
- [ ] cmath — Mathematical functions for complex numbers
- [ ] decimal — Decimal fixed point and floating point arithmetic
- [ ] fractions — Rational numbers
- [ ] random — Generate pseudo-random numbers
- [ ] statistics — Mathematical statistics functions

**Functional Programming Modules**

- [ ] itertools — Functions creating iterators for efficient looping
- [ ] functools — Higher-order functions and operations on callable objects
- [ ] operator — Standard operators as functions

**File and Directory Access**

- [ ] pathlib — Object-oriented filesystem paths
- [ ] os.path — Common pathname manipulations
- [ ] fileinput — Iterate over lines from multiple input streams
- [ ] stat — Interpreting stat() results
- [ ] filecmp — File and Directory Comparisons
- [ ] tempfile — Generate temporary files and directories
- [ ] glob — Unix style pathname pattern expansion
- [ ] fnmatch — Unix filename pattern matching
- [ ] linecache — Random access to text lines
- [ ] shutil — High-level file operations
- [ ] macpath — Mac OS 9 path manipulation functions

**Data Persistence**

- [ ] pickle — Python object serialization
- [ ] copyreg — Register pickle support functions
- [ ] shelve — Python object persistence
- [ ] marshal — Internal Python object serialization
- [ ] dbm — Interfaces to Unix “databases”
- [ ] sqlite3 — DB-API 2.0 interface for SQLite databases

**Data Compression and Archiving**

- [ ] zlib — Compression compatible with gzip
- [ ] gzip — Support for gzip files
- [ ] bz2 — Support for bzip2 compression
- [ ] lzma — Compression using the LZMA algorithm
- [ ] zipfile — Work with ZIP archives
- [ ] tarfile — Read and write tar archive files

**File Formats**

- [ ] csv — CSV File Reading and Writing
- [ ] configparser — Configuration file parser
- [ ] netrc — netrc file processing
- [ ] xdrlib — Encode and decode XDR data
- [ ] plistlib — Generate and parse Mac OS X .plist files

**Cryptographic Services**

- [ ] hashlib — Secure hashes and message digests
- [ ] hmac — Keyed-Hashing for Message Authentication
- [ ] secrets — Generate secure random numbers for managing secrets

**Generic Operating System Services**

- [ ] os — Miscellaneous operating system interfaces
- [ ] io — Core tools for working with streams
- [ ] time — Time access and conversions
- [ ] argparse — Parser for command-line options, arguments and sub-commands
- [ ] getopt — C-style parser for command line options
- [ ] logging — Logging facility for Python
- [ ] logging.config — Logging configuration
- [ ] logging.handlers — Logging handlers
- [ ] getpass — Portable password input
- [ ] curses — Terminal handling for character-cell displays
- [ ] curses.textpad — Text input widget for curses programs
- [ ] curses.ascii — Utilities for ASCII characters
- [ ] curses.panel — A panel stack extension for curses
- [ ] platform — Access to underlying platform’s identifying data
- [ ] errno — Standard errno system symbols
- [ ] ctypes — A foreign function library for Python

**Concurrent Execution**

- [ ] threading — Thread-based parallelism
- [ ] multiprocessing — Process-based parallelism

**The concurrent package**

- [ ] concurrent.futures — Launching parallel tasks
- [ ] subprocess — Subprocess management
- [ ] sched — Event scheduler
- [ ] queue — A synchronized queue class
- [ ] ```_thread``` — Low-level threading API
- [ ] ```_dummy_thread``` — Drop-in replacement for the _thread module
- [ ] dummy_threading — Drop-in replacement for the threading module
- [ ] contextvars — Context Variables

**Context Variables**


**Manual Context Management**

- [ ] asyncio support

**Networking and Interprocess Communication**

- [ ] asyncio — Asynchronous I/O
- [ ] socket — Low-level networking interface
- [ ] ssl — TLS/SSL wrapper for socket objects
- [ ] select — Waiting for I/O completion
- [ ] selectors — High-level I/O multiplexing
- [ ] asyncore — Asynchronous socket handler
- [ ] asynchat — Asynchronous socket command/response handler
- [ ] signal — Set handlers for asynchronous events
- [ ] mmap — Memory-mapped file support

**Internet Data Handling**

- [ ] email — An email and MIME handling package
- [ ] json — JSON encoder and decoder
- [ ] mailcap — Mailcap file handling
- [ ] mailbox — Manipulate mailboxes in various formats
- [ ] mimetypes — Map filenames to MIME types
- [ ] base64 — Base16, Base32, Base64, Base85 Data Encodings
- [ ] binhex — Encode and decode binhex4 files
- [ ] binascii — Convert between binary and ASCII
- [ ] quopri — Encode and decode MIME quoted-printable data
- [ ] uu — Encode and decode uuencode files

**Structured Markup Processing Tools**

- [ ] html — HyperText Markup Language support
- [ ] html.parser — Simple HTML and XHTML parser
- [ ] html.entities — Definitions of HTML general entities

**XML Processing Modules**

- [ ] xml.etree.ElementTree — The ElementTree XML API
- [ ] xml.dom — The Document Object Model API
- [ ] xml.dom.minidom — Minimal DOM implementation
- [ ] xml.dom.pulldom — Support for building partial DOM trees
- [ ] xml.sax — Support for SAX2 parsers
- [ ] xml.sax.handler — Base classes for SAX handlers
- [ ] xml.sax.saxutils — SAX Utilities
- [ ] xml.sax.xmlreader — Interface for XML parsers
- [ ] xml.parsers.expat — Fast XML parsing using Expat

**Internet Protocols and Support**

- [ ] webbrowser — Convenient Web-browser controller
- [ ] cgi — Common Gateway Interface support
- [ ] cgitb — Traceback manager for CGI scripts
- [ ] wsgiref — WSGI Utilities and Reference Implementation
- [ ] urllib — URL handling modules
- [ ] urllib.request — Extensible library for opening URLs
- [ ] urllib.response — Response classes used by urllib
- [ ] urllib.parse — Parse URLs into components
- [ ] urllib.error — Exception classes raised by urllib.request
- [ ] urllib.robotparser — Parser for robots.txt
- [ ] http — HTTP modules
- [ ] http.client — HTTP protocol client
- [ ] ftplib — FTP protocol client
- [ ] poplib — POP3 protocol client
- [ ] imaplib — IMAP4 protocol client
- [ ] nntplib — NNTP protocol client
- [ ] smtplib — SMTP protocol client
- [ ] smtpd — SMTP Server
- [ ] telnetlib — Telnet client
- [ ] uuid — UUID objects according to RFC 4122
- [ ] socketserver — A framework for network servers
- [ ] http.server — HTTP servers
- [ ] http.cookies — HTTP state management
- [ ] http.cookiejar — Cookie handling for HTTP clients
- [ ] xmlrpc — XMLRPC server and client modules
- [ ] xmlrpc.client — XML-RPC client access
- [ ] xmlrpc.server — Basic XML-RPC servers
- [ ] ipaddress — IPv4/IPv6 manipulation library

**Multimedia Services**

- [ ] audioop — Manipulate raw audio data
- [ ] aifc — Read and write AIFF and AIFC files
- [ ] sunau — Read and write Sun AU files
- [ ] wave — Read and write WAV files
- [ ] chunk — Read IFF chunked data
- [ ] colorsys — Conversions between color systems
- [ ] imghdr — Determine the type of an image
- [ ] sndhdr — Determine type of sound file
- [ ] ossaudiodev — Access to OSS-compatible audio devices

**Internationalization**

- [ ] gettext — Multilingual internationalization services
- [ ] locale — Internationalization services

**Program Frameworks**

- [ ] turtle — Turtle graphics
- [ ] cmd — Support for line-oriented command interpreters
- [ ] shlex — Simple lexical analysis

**Graphical User Interfaces with Tk**

- [ ] tkinter — Python interface to Tcl/Tk
- [ ] tkinter.ttk — Tk themed widgets
- [ ] tkinter.tix — Extension widgets for Tk
- [ ] tkinter.scrolledtext — Scrolled Text Widget
- [ ] IDLE
- [ ] Other Graphical User Interface Packages**

**Development Tools**

- [ ] typing — Support for type hints
- [ ] pydoc — Documentation generator and online help system
- [ ] doctest — Test interactive Python examples
- [ ] unittest — Unit testing framework
- [ ] unittest.mock — mock object library
- [ ] unittest.mock — getting started
- [ ] 2to3 - Automated Python 2 to 3 code translation
- [ ] test — Regression tests package for Python
- [ ] test.support — Utilities for the Python test suite
- [ ] test.support.script_helper — Utilities for the Python execution tests

**Debugging and Profiling**

- [ ] bdb — Debugger framework
- [ ] faulthandler — Dump the Python traceback
- [ ] pdb — The Python Debugger

**The Python Profilers**

- [ ] timeit — Measure execution time of small code snippets
- [ ] trace — Trace or track Python statement execution
- [ ] tracemalloc — Trace memory allocations

**Software Packaging and Distribution**

- [ ] distutils — Building and installing Python modules
- [ ] ensurepip — Bootstrapping the pip installer
- [ ] venv — Creation of virtual environments
- [ ] zipapp — Manage executable Python zip archives

**Python Runtime Services**

- [ ] sys — System-specific parameters and functions
- [ ] sysconfig — Provide access to Python’s configuration information
- [ ] builtins — Built-in objects
- [ ] ```__main__``` — Top-level script environment
- [ ] warnings — Warning control
- [ ] dataclasses — Data Classes
- [ ] contextlib — Utilities for with-statement contexts
- [ ] abc — Abstract Base Classes
- [ ] atexit — Exit handlers
- [ ] traceback — Print or retrieve a stack traceback
- [ ] ```__future__``` — Future statement definitions
- [ ] gc — Garbage Collector interface
- [ ] inspect — Inspect live objects
- [ ] site — Site-specific configuration hook

**Custom Python Interpreters**

- [ ] code — Interpreter base classes
- [ ] codeop — Compile Python code

**Importing Modules**

- [ ] zipimport — Import modules from Zip archives
- [ ] pkgutil — Package extension utility
- [ ] modulefinder — Find modules used by a script
- [ ] runpy — Locating and executing Python modules
- [ ] importlib — The implementation of import

**Python Language Services**

- [ ] parser — Access Python parse trees
- [ ] ast — Abstract Syntax Trees
- [ ] symtable — Access to the compiler’s symbol tables
- [ ] symbol — Constants used with Python parse trees
- [ ] token — Constants used with Python parse trees
- [ ] keyword — Testing for Python keywords
- [ ] tokenize — Tokenizer for Python source
- [ ] tabnanny — Detection of ambiguous indentation
- [ ] pyclbr — Python class browser support
- [ ] py_compile — Compile Python source files
- [ ] compileall — Byte-compile Python libraries
- [ ] dis — Disassembler for Python bytecode
- [ ] pickletools — Tools for pickle developers

**Miscellaneous Services**

- [ ] formatter — Generic output formatting

**MS Windows Specific Services**

- [ ] msilib — Read and write Microsoft Installer files
- [ ] msvcrt — Useful routines from the MS VC++ runtime
- [ ] winreg — Windows registry access
- [ ] winsound — Sound-playing interface for Windows

**Unix Specific Services**

- [ ] posix — The most common POSIX system calls
- [ ] pwd — The password database
- [ ] spwd — The shadow password database
- [ ] grp — The group database
- [ ] crypt — Function to check Unix passwords
- [ ] termios — POSIX style tty control
- [ ] tty — Terminal control functions
- [ ] pty — Pseudo-terminal utilities
- [ ] fcntl — The fcntl and ioctl system calls
- [ ] pipes — Interface to shell pipelines
- [ ] resource — Resource usage information
- [ ] nis — Interface to Sun’s NIS (Yellow Pages)
- [ ] syslog — Unix syslog library routines

**Superseded Modules**

- [ ] optparse — Parser for command line options
- [ ] imp — Access the import internals

**Undocumented Modules**

- [ ] Platform specific modules**

# Fundamental 3rd Party
- Requests

# Topics
Common topics to be mastered:

## Web
- [ ] Django (unfortunately web projects need Django a lot!)
- [ ] Flask
- [ ] Building RESTFUL Apis
- [ ] Auth
- [ ] ecommerce integration

## Image Manipulation And Processing
- [ ] Pillow
- [ ] scikit-image

## Gui
- [ ] Qt/PySide
- [ ] wxPython

## WebScraping
- [ ] Scrapy
- [ ] BeautifulSoup
- [ ] Selenium

## OCR
- [ ] Tesseract
- [ ] Others ways apart from Tesseract (Yes that happens to be in the description)

## Data Science
- [ ] Numpy
- [ ] Pandas
- [ ] Matplotlib
- [ ] Seaborn

## Machine Learning
With associated coding. Poor me the expectations of a Python programmer is high.

**Supervised**

_concepts_

- [ ] gradient descent, stochastic gradient descent, cost function, enthropy, gain, overfitting, pruning, kernel trick

_classification_

- [ ] Logistic Regression
- [ ] Supervised Clustering

_regression_

- [ ] Linear Regression
- [ ] Multivariate Linear Regression
- [ ] See also: Polynomial, Ridge and Lasso

_mixed_

- [ ] Tree-based
- [ ] Random Forest
- [ ] Neural Networks
- [ ] Support Vector Machines

**Unsupervised**
- [ ] TODO

**Reinforcement Learning**
- [ ] TODO

**GAN**
- [ ] TODO

## Computer Vision
- [ ] OpenCV

# Algorithms
- [ ] TODO

