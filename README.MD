# This repo contains my quick notes from what I learnt new in the PyConIndia2020.

- [Contents](#Contents)
	* [Awesome-CommandLine-Tools](#Awesome-CommandLine-Tools)
	* [How-to-make-data-apps-seem-faster](#How-to-make-data-apps-seem-faster)
    * [Static-Typing-Python](#Static-Typing-Python)
    * [Logging](#Logging)
	* [Some-side-notes](#Some-side-notes)


## 1. Awesome-CommandLine-Tools

Presentation slides *./Awesome CommandLine Tools.pdf*


*REPL --> Read, Eval, Print, Loop*

*python package --> prompt_toolkit (creating a commandline tool)*

https://github.com/prompt-toolkit/python-prompt-toolkit 

*pygments package --> for lexers*

### CHECKLIST (consedration while making commandline tools) 
1. Persistent History
2. History search
3. Emacs Keybindings
4. Auto-Completion
5. Minimal Config
6. Syntax Coloring

### Resources 
1. dbcli.com ; pgcli.com ; mycli.net ; Litecli.com ; iredis.io 
2. fishshell.com (design)
3. bpython-interpreter.org
4. prompt-toolkit



## 2. How-to-make-data-apps-seem-faster

REPO used for presentation --> https://github.com/sanand0/pyconindia2020 

1. Logging (to check progress)
2. TQDM (to show progress)
3. Websocket --> from gramex
4. SQL-LITE-DICT (save results and avoid recomputing)
https://pythonhosted.org/sqlite_object/sqlite_dict.html 


### Explore
1. Forward-recovery (what is this in context of programming ?)
2. Apache Plasma (EXPLORE)
3. Comicgen --> Front-End (EXPOLRE)
https://github.com/gramener/comicgen/ 




## 3. Static-Typing-Python

1. Detailed article on typing https://realpython.com/python-type-checking/ 

Python annotations (type hints)
the typing module --> https://docs.python.org/3/library/typing.html 
mypy python module enforce static typing 

2. MonkeyType (MonkeyType collects runtime types of function arguments and return values, and can automatically generate stub files or even add draft type annotations directly to your Python code based on the types collected at runtime.)
https://github.com/Instagram/MonkeyType 




## 4. Logging

Presentation slides *./Logging_the_right_way_.pdf* 

1. Structlog (Drop in replacement to standard logging library)
https://www.structlog.org/en/stable/getting-started.html 

2. Dynamic logging
 * Change Log Level in Run time
    - logging.config.listen(<port>)
       - Works with fileConfig, dictConfig etc

3. Recipies for logging 
 - https://docs.python.org/2/howto/logging-cookbook.html#configuration-server-example 
 - https://medium.com/hiredscore-engineering/logging-lets-do-it-right-41d568d3bfcd



## 5. Some-side-notes

### a. Unbound local error in python
https://docs.python.org/3/faq/programming.html#why-am-i-getting-an-unboundlocalerror-when-the-variable-has-a-value

### b. Celery (Task Queues)
https://docs.celeryproject.org/en/stable/getting-started/introduction.html

### c. Hypothesis (testing framework python)
https://hypothesis.readthedocs.io/en/latest/

### d. Renpy for making games(episodic)
https://www.renpy.org/dev-doc/html/python.html
https://krita.org/en/ --> *ART*