# $OpenBSD$

COMMENT =	adds CPAN Testers reporting to CPAN.pm
DISTNAME =	CPAN-Reporter-1.2018
PKG_ARCH =	*
CATEGORIES =	sysutils

# Apache 2.0
PERMIT_PACKAGE =	Yes

MODULES =	cpan

RUN_DEPENDS =		devel/p5-Config-Tiny>=2.08 \
			devel/p5-Devel-Autoflush>=0.04 \
			devel/p5-File-HomeDir>=0.58 \
			devel/p5-Probe-Perl \
			devel/p5-Test-Reporter>=1.54 \
			sysutils/p5-Capture-Tiny
TEST_DEPENDS =		devel/p5-File-Copy-Recursive>=0.35 \
			devel/p5-File-pushd>=0.32 \
			devel/p5-IO-CaptureOutput>=1.03

.include <bsd.port.mk>
