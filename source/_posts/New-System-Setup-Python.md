---
title: New System Setup - Python and AI
date: 2019-01-02 15:29:50
tags: 
- Setup
- Python
categories:
- Setup
- Python
---

## Installing Python

goto <https://www.python.org/downloads/> and download lastest version

IMPORTANT - you need to select 64 bit to do AI (due to tensorflow requirements)

As of this initial post, the Tensorflow requirement is 3.5 or 3.6, but not 3.7 version of python

> I usually add python to path (this isn't the default)

copy the following to batch file and run

> NOTE: I installed python 3.6 to all users location via elevation.  I had problem installing the packages below until I added --user to install to user's folder

```
pip -V
pip install --user tensorflow
pip install --user pandas
pip install --user keras
pip install --user graphviz
pip install --user pydot
pip install --user h5py
pause
```
# Good Reference Sites

+ https://www.python.org/downloads/
+ https://github.com/pandas-dev/pandas
+ http://pandas.pydata.org/   
+ https://pypi.python.org/pypi/pandas 
+ https://pypi.python.org/pypi/pydot
+ https://pypi.python.org/pypi/graphviz
+ http://www.h5py.org/
+ https://keras.io/#installation 
+ https://pypi.python.org/pypi/Keras