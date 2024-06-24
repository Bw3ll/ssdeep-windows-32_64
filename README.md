ssdeep Python Wrapper for Windows
=================================

Fork includes `fuzzy_64.dll` allowing the ssdeep to run on 32 and 64 bit python.

#### Install:

1. Download (and extract) / clone this repo into a folder.
2. In said folder run `python setup.py install`.
3. If six is not installed, you may need to manually do it, e.g. `python -m pip install six`

ssdeep by Jesse Kornblum (http://ssdeep.sourceforge.net).
Inspired by python-ssdeep (https://github.com/DinoTools/python-ssdeep).

This is a minor fork of Jeese's work to correct some minor issues for compatibility with SHAREM. SHAREM was developed using Jesse's, and if it works, it works - but in some installs, there were some extremely minor changes that needed to be made dealing with the library six.
