### python [python-first-steps](realpython.com/learn/python-first-steps/)

### Windows10

### AnacondaPython
click on python.exe to open the interactive python shell
type "exit() to exit the interactive python shell


### SublimeText3 [setting-up-sublime-text-3-for-full-stack-python-development](https://realpython.com/setting-up-sublime-text-3-for-full-stack-python-development/)

  [DOSKEY](https://en.wikipedia.org/wiki/DOSKEY)   doskey subl="C:\Program Files\Sublime Text 3\sublime_text.exe" $*

   Open the current directory.
  $ subl .

  Open a directory called tests.
  $ subl ~/Documents/test

  Open a file called text.txt.
  $ subl test.txt

  If there are spaces in the path, you must surround the entire path in double quote  s:

  $ subl "~/Documents/test/my test file.txt"
  
### Linting 

Lint-like tools are especially useful for interpreted languages like JavaScript and Python. Because such languages lack a compiling phase that displays a list of errors prior to execution, the tools can also be used as simple debuggers for common errors (e.g. syntactic discrepancies) as well as hard-to-find errors such as heisenbugs (drawing attention to suspicious code as "possible errors")

### Python Idioms = Happy Coding
PEP 8 – Style Guide for Python Code is the style guide for programming Python code. Study this.

One idiom that trips up many new Python developers is indentation. Python uses indentation (4 spaces) to logically organize code into sections called [code blocks](http://en.wikipedia.org/wiki/Block_(programming). A code block starts with an indent and ends with a dedent (un-indent?). Incorrect indentation will generate an error in Python preventing your code from executing. And this is exactly where having a properly setup code editor pays off, since it will catch indentation errors and highlight them for you. You should also use spaces instead of tabs when indenting. Most editors will allow you to convert tabs to spaces, so that when you tab it is actually applying 4 spaces.
