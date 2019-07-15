# pythonista-checklist
What you **need** to be a Pro Python Programmer

Included: freelancer.com projects analysis and codementor.io freelancer interviewer guides.

Freelancing requires some tough skills, beyond casual programming. This checklist aims at helping with skilling-up.

[... in progress] 

**Practical Use**: Keep a copy of the readme and check the list as you go. But keep those in mind:
- You won't complete it overnight.
- Don't wait to complete it to start freelancing.
- You skill up by doing.
- Learning frameworks is as important as learning a lanuguage.

# Index

- Core
- Std Lib
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
- [ ] **dunder builtins:** ```__build_class__, __debug__, __doc__, __import__, __loader__, __name__, __package__, __spec__```

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

**lambdas**
- [ ] assigned to variables
- [ ] without arg, with arg, with muliple arguments
- [ ] keywords with lambdas

>>> dir("a")
'__add__', '__class__', '__contains__', '__delattr__', '__dir__', '__doc__', '_
_eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__getnewargs
__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__iter__', '__le__'
, '__len__', '__lt__', '__mod__', '__mul__', '__ne__', '__new__', '__reduce__',
'__reduce_ex__', '__repr__', '__rmod__', '__rmul__', '__setattr__', '__sizeof__'
, '__str__', '__subclasshook__', 'capitalize', 'casefold', 'center', 'count', 'e
ncode', 'endswith', 'expandtabs', 'find', 'format', 'format_map', 'index', 'isal
num', 'isalpha', 'isascii', 'isdecimal', 'isdigit', 'isidentifier', 'islower', '
isnumeric', 'isprintable', 'isspace', 'istitle', 'isupper', 'join', 'ljust', 'lo
wer', 'lstrip', 'maketrans', 'partition', 'replace', 'rfind', 'rindex', 'rjust',
 'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip',
 'swapcase', 'title', 'translate', 'upper', 'zfill'

