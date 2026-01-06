# Learning Acyclic Programs Project

You can find the instructions of the project in the file [acyclic-programs.ipynb](acyclic-programs.ipynb).

To submit your solution, please modify the file [acyclic-programs.lp](asp/acyclic-programs.lp) of the directory [asp](asp) with your encoding.

Every time you push a new commit, your solution will be tested automatically.
The timeout per instance is `100` seconds, and
the actual command call for the test is:
* ``python asp/test.py -e asp/acyclic-programs.lp -i asp/instances -s asp/solutions -opt -t 100 -m 250``

For help, type `python asp/test.py --help`.

After the tests are run, you will be able to see the results in the **Actions** tab:
* Select one of the tests, click in run-autograding-tests and go to the tab "Print output"
