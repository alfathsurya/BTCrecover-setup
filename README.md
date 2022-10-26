# BTCrecover-setup
 How to setup BTCrecover on Windows

First before you can run BTCrecover you need to install its Prerequisites, here is what you will need to install.

You need to install Python 2.7.18 and add python.exe to path 
link to Python 2 - https://www.python.org/downloads/release/python-2718/

Then you need to update pip using the command - python -m pip install --upgrade pip

Then if you have a GPU, download the pyopencl‑2018.1.1+cl12‑cp27‑cp27m‑win_amd64.whl from
- https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyopencl  (I have included this file in the download)


and then move the .whl file to a folder and open cmd in that folder

then do the commands - 
                       pip install pycryptodome

                       pip install cryptography 

                       pip install pyopencl-2018.1.1+cl12-cp27-cp27m-win_amd64.whl (run this if you have a GPU)
 


Now you can run BTCrecover.py to start cracking.

@Rysndavjd



