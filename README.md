# Distributed-computing-Parallel-Processing
My trials with multiprocessing in python and parallel processing with the supercomputer

## For a python multiprocessing code to run we have to add the following code else the excecutable will be directed to the folder in whch the python code resides.

import multiprocessing

multiprocessing.set_executable(os.path.join(sys.exec_prefix, 'pythonw.exe'))
