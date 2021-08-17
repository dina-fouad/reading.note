## Regular Expressions in Python
In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import:
```
import re
```

## Basic Patterns: Ordinary Characters
You can easily tackle many basic patterns in Python using ordinary characters. Ordinary characters are the simplest regular expressions. They match themselves exactly and do not have a special meaning in their regular expression syntax.

Examples are 'A', 'a', 'X', '5'.

## Wild Card Characters: Special Characters
Special characters are characters that do not match themselves as seen but have a special meaning when used in a regular expression. For simple understanding, they can be thought of as reserved metacharacters that denote something else and not what they look like.

Let's check out some examples to see the special characters in action...

But before you do, the examples below make use of two functions namely: search() and group().

## Repetitions
It becomes quite tedious if you are looking to find long patterns in a sequence. Fortunately, the re module handles repetitions using the following special characters:

+ - Checks if the preceding character appears one or more times starting from that position.


# shutil — High-level File Operations
- Copying Files
copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.

- Copying File Metadata
By default when a new file is created under Unix, it receives permissions based on the umask of the current user. To copy the permissions from one file to another, use copymode().

- Working With Directory Trees
shutil includes three functions for working with directory trees. To copy a directory from one place to another, use copytree(). It recurses through the source directory tree, copying files to the destination. The destination directory must not exist in advance.

- Finding Files
The which() function scans a search path looking for a named file. The typical use case is to find an executable program on the shell’s search path defined in the environment variable PATH.

- Archives
Python’s standard library includes many modules for managing archive files such as tarfile and zipfile.