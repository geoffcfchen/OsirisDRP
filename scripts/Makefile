################################################################################
#+
#  Module:	$KSSDIR/osiris/drs/scripts
#
#  Revisions:   
#
#  Author:	Jason Weiss
#
#  Date:	2005/09/21
#
#  Description:	Makefile for OSIRIS DRS scripts
#-
################################################################################

#  Include files.

INCLUDE	= 

#  C source and object files.
CFLAGS  = 

SOURCE = osirisDropDRF \
	 osirisDRPSetupEnv \
         osirisOfflineDRP \
	 run_odrp \
         run_offline_drp

OBJECT	= 

DIRS	= 

#  Files to make are ...
FILES	= 

#  Files to release are ...
RELFILES  = $(SOURCE)

#  This is a release point. Define version macros to override values inherited
#  from the environment.

override SYSNAM = kss/osiris/drs/scripts/
override VERNUM = 4.1 

#  Include general make rules (use /etc if no environment variable).

include $(KROOT)/etc/config.mk

