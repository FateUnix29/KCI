Kano Creation Interface (KCI)
+++++++++++++++++++++++++++++++

A Python abstraction of the .brv and .brm file formats.



What is this?
===============

KCI is a ""fork"" (really an entire rewrite) of the BRCI (Brick Rigs Creation Interface) project, by one of it's own developers.
I wasn't particularly active in the development of BRCI, therefore, I decided I might as well do *something*.

*BRCI* is a Python library for the manipulation of .brv files -
The file format for vehicles in the game *Brick Rigs*.
It was also able to parse .brm files, which were the metadata files for the vehicle.
It could even add the preview images to the vehicles.

At the time of writing, BRCI is broken, and it seems to me rather messy.

KCI is my own attempt at BRCI. Since I have cleaner code styling, and I've gotten quite good at Python, I've decided to rewrite it.



Disclaimer
============

Under no circumstances should you actually use this project.
It most likely does not even work.

Right now, I'm not taking it *particularly* seriously, and as a result, it might not even ever get to writing a .brv file.
If it does though, you know the risks. Feel free to use it.

Additionally, KCI was developed on Linux. I will make attempts to make it crossplatform, including adding fallbacks if ~/.steam is not found.
For Windows, as 'cross-platform' suggests, it *should* work. Pathing is simple enough.



Requirements/Dev Environment
==============================

You are unlikely to actually need to install dependencies manually, but in case you do, this should be an up-to-date list of what you'll need.

================== =============== =====================================================================================
       Name            Version                                            Why
================== =============== =====================================================================================
Python             3.13.0+         KCI was developed on Python 3.13.3. No guarantees any lower version works.
================== =============== =====================================================================================


Speculative Dependencies
--------------------------

================== =============== =====================================================================================
       Name            Version                                            Why
================== =============== =====================================================================================
NumPy              2.0.0+          While not actually required right now, it probably will be a dependency in the future.
================== =============== =====================================================================================



Installation
==============

KCI is equipped with a pyproject. No manual installation required other than cloning the repository.
Github doesn't seem to be able to render .rst codeblocks, therefore, I've made a README_C.md file. Look for the code block marked with '1. Install'.



Usage Example
===============

A small usage example.
The code block is marked with '2. Usage Example' in README_C.md.