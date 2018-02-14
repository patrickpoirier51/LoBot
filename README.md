# LoBot
The goal of the Robolocust project is to design and implement a robot that 
avoids obstacles based on a model of the Lobula Giant Movement Detector (LGMD) 
found in locust brains.
   
Source: http://ilab.usc.edu/cgi-bin/secure/viewcvs.cgi/trunk/saliency/src/Robots/LoBot/

Papers:

https://arxiv.org/pdf/1801.04530.pdf

http://eprints.lincoln.ac.uk/25279/1/20 ... Bfinal.pdf


Robolocust supports several different models of the locust's LGMD.
This setting specifies which of these LGMD implementations should be
used. Further settings related to the chosen model usually go in an
identically named section. Thus, for example, the Stafford model
settings will be in the [stafford] section; settings specific to the
Gabbiani model will be in the [gabbiani] section; so on and so forth.

see /LoBot/config/lobot.conf

