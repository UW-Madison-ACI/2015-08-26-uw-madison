---
layout: page
title: Test Your Software Installation
root: ..
---

Open a command prompt window.  This will be "Terminal", for Mac and Linux users 
and the "GitBash" program for Windows users.  

Type the following commands into the window to check whether your software has 
installed correctly.  

~~~
git --version
python --version
nano --help
python -c "import nose"
python -c "import numpy"
python -c "import matplotlib"
~~~

Also try one of the two commands below: 
~~~
jupyter --version
~~~
OR
~~~
ipython --version
~~~

Each command should print some sort of information about the version of the program, 
or a list of options that the program uses.  The `python -c` statements shouldn't print 
anything.  

If you see a message like: 
~~~
-bash: git: command not found
~~~
or
~~~
ImportError: No module named nose
~~~

Then something has gone wrong with the installation.  