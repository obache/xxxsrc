# $NetBSD: Makefile,v 1.75 2021/04/21 11:41:44 adam Exp $

DISTNAME=		kye-1.0
PKGREVISION=		36
CATEGORIES=		games
MASTER_SITES=		http://games.moria.org.uk/kye/download/

MAINTAINER=		pkgsrc-users@NetBSD.org
#HOMEPAGE=		http://games.moria.org.uk/kye/pygtk
COMMENT=		Puzzle game

DEPENDS+=		${PYPKGPREFIX}-gtk2-[0-9]*:../../x11/py-gtk2
DEPENDS+=		librsvg-[0-9]*:../../graphics/librsvg

USE_LANGUAGES=		#

SUBST_CLASSES+=		prefix
SUBST_STAGE.prefix=	pre-configure
SUBST_FILES.prefix=	kye/common.py
SUBST_SED.prefix=	's|@PREFIX@|${PREFIX}|g'

PYTHON_VERSIONS_ACCEPTED=	27 # py-gtk2

.include "../../lang/python/application.mk"
.include "../../lang/python/distutils.mk"
.include "../../mk/bsd.pkg.mk"
