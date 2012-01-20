#GENGETOPT = @gengetopt@

bin_PROGRAMS=pentatelnet



pentatelnet_SOURCES = telnetd.c
pentatelnet_CFLAGS  = $(LIBEVENTSTUFF_CFLAGS) $(AM_CFLAGS)
pentatelnet_LDFLAGS = $(LIBEVENTSTUFF_LIBS)

include_HEADERS=  #not having one yet except generated config

#no option parser yet.
#If somebody knows how to avoid this hack, please contact...
#dist_noinst_DATA=options.ggo 
#options.c: options.ggo
#options.h: options.ggo

##ifneq ($(GENGETOPT),"false")
#.ggo.c:
#	$(GENGETOPT) -F ${@:%.c=%} < $<
#	LANG=C sed -i -e 's/..&@//g' $@ ${@:%.c=%.h}
##endif


EXTRA_DIST= #nothing yet
