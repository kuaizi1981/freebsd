# From:	@(#)Makefile	8.1 (Berkeley) 6/4/93
# $FreeBSD$

PROG=	rshd
MAN=	rshd.8

WARNS?=	3
WFORMAT=0

DPADD=	${LIBUTIL} ${LIBPAM}
LDADD=	-lutil ${MINUSLPAM}

.include <bsd.prog.mk>
