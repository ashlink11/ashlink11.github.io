programming: i/o & processing

### frontend
javascript typescript npm yarn webpack parcel
design systems component libraries
common npm packages

### middleware/backend
docker kubernetes linux devops CI/CD jenkins github webhooks python

Random questions: I wonder: do most large companies' IT/devops use scripting to bundle npm dependencies? and maybe mid-sized companies use scripting to configure a bundler like webpack? and then startups work with pre-built template apps? It's pretty daunting to think about the number of libraries/packages that needs to be run in a browser or mobile browser to make an app work and I'm so excited to see how script-writers (?) accomplish it and work around migrations and evolving code.

6/26 - notes

fundamentals of programming concepts including data types, variables, decision statements, loops, functions and file handling

i/o (file handling using all the rest)

processing (not as much file handling)

common scripting language constructs: lists, literals, regular expressions

incrementally evolving ai from python to other languages 

variables/literals - integers, floats and strings

This package will install Python 3.11.4 for macOS 10.9 or later for the following architecture(s): arm64, x86_64.

Reserved keywords python

False      await      else       import     pass
None       break      except     in         raise
True       class      finally    is         return
and        continue   for        lambda     try
as         def        from       nonlocal   while
assert     del        global     not        with
async      elif       if         or         yield

{:.2f} two decimal place formatting

x % 10000 yield last four digits

script is a file; can be input to the interpreter
module: a file imported by a script, module or interpreter
math module: theoretic, trigonometric, and logarithmic operations

unicode representation = "code point" (over 1m code points which each have a decimal encoding) (ord() and chr())

r = raw string
, end='' = no newline
, sep='' = no spaces btw args
, flush=True = can help with buffer errors

https://docs.python.org/3.7/howto/unicode.html

lists, tuples, and dictionaries

"Data types: String basics, list basics, dictionary basics, types summary, additional practice, type conversions

Strings: String formatting, advanced string formatting, string slicing, string methods, string split and join"

default_is_string = input('optional prompt')

len()

strings: immutable; must use assignment to update entire string

list.append(value)
list.pop(i)
list.remove(value)

dict: key is immutable type (e.g.: number, string, tuple) and value is any type

KeyError

containers:
mapping types (dict) and sequence types: string, list (mutable), tuple ((use len() and []))

relational operators (<, <=, >, >=), equality operators (==, !=), membership operators (in, not in), and identity operators (is, is not)

"Good practice is to always use the equality operator== when comparing values."

input_string = input().strip().lower().slice() 
parse input tokens

