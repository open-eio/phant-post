phant-post
==========

Python script for posting a random number to Sparkfun's 'phant' service; html code for plotting the resultant data.

I followed the instructions here to create a new data stream on the phant service -- which yields a 'public' and 'private' key:

https://learn.sparkfun.com/tutorials/pushing-data-to-datasparkfuncom/introduction

I then created a python script, "phant.py" that sends a random number to this service (see python script in this repository), following the instructions provided for the Raspberry Pi (but simply uses Python, which would work on any system that supports Python):

https://learn.sparkfun.com/tutorials/pushing-data-to-datasparkfuncom/raspberry-pi-python

The resultant dataset is here:

https://data.sparkfun.com/streams/9JyZ00pQg7iDyOYaWDrv

I then created an html page ("graph.html") that uses the Google Charts and Sparkfun's 'phant' service, following the instructions here:

http://phant.io/graphing/google/2014/07/07/graphing-data/

The resultant page example is here:

http://pvos.org/graph.html

