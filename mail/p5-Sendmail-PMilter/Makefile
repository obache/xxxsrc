# $NetBSD: Makefile,v 1.26 2021/05/24 19:52:51 wiz Exp $
#

DISTNAME=	Sendmail-PMilter-1.00
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	9
CATEGORIES=	mail perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=../../authors/id/A/AV/AVAR/}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://metacpan.org/release/Sendmail-PMilter
COMMENT=	Pure-Perl Milter protocol API

# Though it doesn't exist yet, just in case:
CONFLICTS+=	p5-Sendmail-Milter-[0-9]*

MAKE_ENV+=	PERL_MM_USE_DEFAULT=1

PERL5_PACKLIST=	auto/Sendmail/PMilter/.packlist

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
