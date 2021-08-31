![pack](https://cdn.programiz.com/sites/tutorial2program/files/PackageModuleStructure.jpg)
#packages in python: 
A package is basically a directory with Python files and a file with the name __init__ . py. This means that every directory inside of the Python path, which contains a file named __init__ . py, will be treated as a package by Python.
##creating packages in python: Let's create a package named mypackage, using the following steps:

Create a new folder named D:\MyApp.
Inside MyApp, create a subfolder with the name 'mypackage'.
Create an empty __init__.py file in the mypackage folder.
Using a Python-aware editor like IDLE, create modules greet.py and functions.py with the following code:
def SayHello(name):
    print("Hello ", name)

sayhello(mam)
##different packages in python:
###tym:
>from datetime import timedelta
d = timedelta(microseconds=-1)
(d.days, d.seconds, d.microseconds)
(-1, 86399, 999999)

###mathematical packages in python:
math.copysign(x, y),
math.fabs(x,y),
math.floor(x)

###random
>Method	Description
sample()	Returns a given sample of a sequence
random()	Returns a random float number between 0 and 1
uniform()	Returns a random float number between two given parameters

