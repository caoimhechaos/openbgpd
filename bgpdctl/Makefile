#	$OpenBSD$

.PATH:		${.CURDIR}/..

PROG=	bgpdctl
BINDIR=	/usr/sbin
SRCS=	bgpdctl.c buffer.c imsg.c log.c
CFLAGS+= -Wall
CFLAGS+= -Wstrict-prototypes -Wmissing-prototypes
CLFAGS+= -Wmissing-declarations -Wredundant-decls
CFLAGS+= -Wshadow -Wpointer-arith -Wcast-qual
CFLAGS+= -Wsign-compare
YFLAGS=
MAN= bgpdctl.8

.include <bsd.prog.mk>
