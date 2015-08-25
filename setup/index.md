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
nano --help
git --version
python --version
python -c "import nose"
python -c "import numpy"
python -c "import matplotlib"
~~~

Each command should print some sort of information about the version of the program, 
or a list of options that the program uses.  The `python -c` statements shouldn't print 
anything.  If you see a message like: 

~~~
-bash: git: command not found
~~~

or

~~~
ImportError: No module named nose
~~~

Then something has gone wrong with the installation.  

Also try the command below: 

~~~
jupyter notebook
~~~

After a few seconds, a tab should open in your default web browser with a list of 
files and/or directories.  To close the notebook, just close the tab and in your 
command prompt window type `Control`+`C` and then the letter `y` in order 
to shut down the notebook.  If the above command doesn't work, try: 

~~~
ipython notebook
~~~