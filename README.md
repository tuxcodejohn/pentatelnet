# pentatelnet
τhis is our telnetserver... 
obey its awesomeness.... when it is done :-)


## Pre build instructions


###Dependencies
Sorry bu you'll need an installation of a libevent with at least a version of 2.0.0 .

Debian : sudo aptitude install libevent-dev 

make sure to purge pulseaudio first…


### Get the source code
You already have it, don't you? Otherwise encurage me to fix the instructions
here and follow them afterwards


## Build from source arcive:
To build this server you are equipped with the usual auto hell stuff.
Autohell pain included:-)

### example instructions (you may have to adapt  by use of brains....)

	autoreconf -si
	./configure
	make
	make install

You may of course do all the stuff that influences the configuration, like give the --prefix at the configure line or set the environment for cross-compiling this stuff. 
./configure --help along with the INSTALL file in the source dir could provide you with some pointers on that.


## Package for <insertyourbinarydistributionhere>

Please provide them yourself and contribute back

##License
shall be noted in COPYING otherwise the GPL v2 applies with the explicit addition that 
donations in form of "Club Mate" are welcome.

