Installing Python
Install Python (version 3.7 or 3.8), if not yet available on your machine:

Download “Windows x86-64 executable installer” for one of these Python versions:

Python 3.7
Python 3.8

Run the installer and follow the prompt

We advise you to check the box to update the PATH or update the PATH manually with the following paths after replacing the Username to your own and using the Python version you installed (here, we assume that the install is limited to the local user and the default install path was used):

  C:\Users\Username\AppData\Local\Programs\Python\Python37
  C:\Users\Username\AppData\Local\Programs\Python\Python37\Scripts


Finally, install required Python packages using pip:
Use the following lines in the command line to do so:

  python -m pip install pip --upgrade
  python -m pip install "numpy==1.19.5" "opencv-python>=4.2.0.34" pytest
