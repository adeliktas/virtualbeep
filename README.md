Virtualbeep
================

A super-simple code snippet I made wih scikit's audiolab to play custom 
frequencies on my speaker. 

Lately, there had been some oddities with the beep command under ubuntu based
distros (some blacklisting issues with the kernel IIRC) and some laptops don't
even support the hardware for regular beep. Since I had some funny beep-powered
shellscripts from past projects (looking at you GIDA) and I didn't have a way
to play them I decided to make this snippet. 


HOW TO USE?
===============

I'm not managing dependencies so you might want to pip install numpy and
scikits.audiolab.

If you have those packages, clone or download this repo and run virtualbeep.py.


[Update] Install and Run
===============

wget https://bootstrap.pypa.io/pip/2.7/get-pip.py

python2.7 get-pip.py

python2 -m pip -V

python2 -m pip install --user numpy

python2 -m pip install --user scikits.audiolab

python2 imperial.py

WARNING: BEEP IS EXTREMELY LOUD, LOWER VOLUME!!!
