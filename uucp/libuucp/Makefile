# This is the Makefile for the libuucp subdirectory of Taylor UUCP
# $FreeBSD$

LIB=		uucp
SRCS = buffer.c crc.c debug.c escape.c getopt.c getop1.c parse.c quote.c \
	quotes.c spool.c status.c xfree.c xmall.c xreall.c

CFLAGS+=	-I$(.CURDIR)/../common_sources

NOMAN=		noman
NOPROFILE=	noprofile

install:

.include <bsd.lib.mk>
