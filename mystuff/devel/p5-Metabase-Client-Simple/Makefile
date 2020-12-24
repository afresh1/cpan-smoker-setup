# $OpenBSD$

COMMENT =	client that submits to Metabase servers

DISTNAME =	Metabase-Client-Simple-0.012
CPAN_AUTHOR =	DAGOLDEN
PKG_ARCH =	*
CATEGORIES =	devel

FIX_EXTRACT_PERMISSIONS =	Yes

# Apache 2.0
PERMIT_PACKAGE =	Yes

MODULES =		cpan

RUN_DEPENDS =		converters/p5-JSON-MaybeXS \
			www/p5-URI
TEST_DEPENDS =		devel/p5-Metabase-Fact

.include <bsd.port.mk>
