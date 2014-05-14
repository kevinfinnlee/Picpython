#Welcome to the wonderful world of Passoft!#

In theory, this entire repository will one day be moved 
to the official PASSCAL SVN. For now, we will leave it
here on github.

###What is picpython?###

Picpython is the Passcal Approved Python package. Once built, 
picpython will essentially be a python package with all the bells
and whistles needed to build and run Passoft. This repository was 
created to automate the tedious process that is building all of
picpython's dependencies by hand.

###Why are these all hard versions of software?###

Passoft's dependencies haven't changed for years. The current 
lab manual recommends software versions much older than the ones
found on this repository. If we absolutely need to update a library,
this repository's build scripts should be versatile enough to allow
for changes.

###How do I build Picpython?###

Do this:
python setup.py [picpython dir]

where [picpython dir] is an absolute path to where you want picpython stored. (usually /opt/passcal/other)
