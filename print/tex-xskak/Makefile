# $NetBSD: Makefile,v 1.3 2019/12/06 20:23:46 markd Exp $

DISTNAME=	xskak
PKGNAME=	tex-${DISTNAME}-1.5
TEXLIVE_REV=	51432

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://ctan.org/pkg/xskak
COMMENT=	Extension to the skak package for chess typesetting
LICENSE=	lppl-1.3c

DEPENDS+=	tex-chessboard-[0-9]*:../../print/tex-chessboard
DEPENDS+=	tex-chessfss-[0-9]*:../../print/tex-chessfss
DEPENDS+=	tex-skak>=1.4:../../print/tex-skak
DEPENDS+=	tex-xifthen-[0-9]*:../../devel/tex-xifthen
DEPENDS+=	tex-xkeyval-[0-9]*:../../print/tex-xkeyval

TEXLIVE_UNVERSIONED=	yes
.include "../../print/texlive/package.mk"
.include "../../mk/bsd.pkg.mk"
