# $NetBSD: Makefile,v 1.3 2021/03/08 08:12:53 jaapb Exp $

GITHUB_PROJECT=	lru
GITHUB_TAG=	v${PKGVERSION_NOREV}
DISTNAME=	${GITHUB_PROJECT}-0.2.0
PKGNAME=	ocaml-${DISTNAME}
PKGREVISION=	1
CATEGORIES=	devel
MASTER_SITES=	${MASTER_SITE_GITHUB:=pqwy/}

MAINTAINER=	jaapb@NetBSD.org
HOMEPAGE=	https://github.com/pqwy/lru/
COMMENT=	Scalable LRU caches for OCaml
LICENSE=	isc

USE_LANGUAGES=	# none

OCAML_USE_TOPKG=	yes
OCAML_USE_OPAM=		yes

.include "../../devel/ocaml-psq/buildlink3.mk"
.include "../../devel/ocamlbuild/buildlink3.mk"
.include "../../mk/ocaml.mk"
.include "../../mk/bsd.pkg.mk"
