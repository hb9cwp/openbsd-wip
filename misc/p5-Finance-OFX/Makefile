# : Makefile,v 1.2 2005/12/01 22:37:28 steven Exp $

COMMENT=		"OFX client implementation"
DISTNAME=		Finance-OFX-2a
PKGNAME=		p5-${DISTNAME}
CATEGORIES=		misc perl5

MAINTAINER=		Todd T. Fries <todd@openbsd.org>

# Artistic
PERMIT_PACKAGE_CDROM=	Yes
PERMIT_PACKAGE_FTP=     Yes
PERMIT_DISTFILES_FTP=   Yes

RUN_DEPENDS+= ${BUILD_DEPENDS}
BUILD_DEPENDS+= devel/p5-Data-GUID

MASTER_SITES=    ${MASTER_SITE_PERL_CPAN:=../../authors/id/B/BF/BFOZ/}

WRKDIST=		${WRKDIR}/Finance-OFX-2

CONFIGURE_STYLE= perl

.include <bsd.port.mk>
