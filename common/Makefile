# $Id$

TOP=	..

SUBDIR=		sys

INCS=		elfdefinitions.h
INCSDIR=	/usr/include

.PHONY:	all clean clobber depend obj

all depend:

cleandepend:
	rm -f ${.OBJDIR}/.depend

.include "${TOP}/mk/elftoolchain.inc.mk"
.include "${TOP}/mk/elftoolchain.subdir.mk"
