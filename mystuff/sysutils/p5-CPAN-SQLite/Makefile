# $OpenBSD$

COMMENT =	maintain and search a minimal CPAN database
DISTNAME =	CPAN-SQLite-0.219
PKG_ARCH =	*
CATEGORIES =	sysutils

# Perl
PERMIT_PACKAGE =	Yes

MODULES =	cpan

RUN_DEPENDS =	databases/p5-DBI \
		databases/sqlite3 \
		devel/p5-CPAN-DistnameInfo \
		devel/p5-File-HomeDir
TEST_DEPENDS =	databases/p5-DBD-SQLite

TEST_DEPENDS +=	devel/p5-Test-Memory-Cycle

pre-test:
	${INSTALL_DATA} ${FILESDIR}/03modlist.data.gz \
	    ${WRKBUILD}/t/cpan/modules/

.include <bsd.port.mk>
