# $OpenBSD$

COMMENT =	turnkey CPAN Testers smoking
DISTNAME =	CPAN-Reporter-Smoker-0.29
PKG_ARCH =	*
CATEGORIES =	sysutils

# Apache 2.0
PERMIT_PACKAGE =	Yes

MODULES =	cpan

RUN_DEPENDS =	devel/p5-Module-Build>=0.30 \
		devel/p5-Probe-Perl>=0.01 \
		devel/p5-Term-Title>=0.01 \
		devel/p5-Test-Reporter>=1.58 \
		sysutils/p5-CPAN-Reporter>=1.1702
TEST_DEPENDS =	devel/p5-CPAN-Checksums \
		devel/p5-IO-CaptureOutput>=1.06

.include <bsd.port.mk>
