# Created by: Victor Pereira <v.pereira@packetwerk.de>
# $FreeBSD$

PORTNAME=	Twig
PORTVERSION=	1.12.3
CATEGORIES=	devel pear
PKGNAMEPREFIX=	pear-Twig
MASTER_SITES=	http://pear.twig-project.org/get/
MAINTAINER=	v.pereira@packetwerk.de
COMMENT=	TWIG Template 

LICENSE=	BSD


BUILD_DEPENDS=	${PEARDIR}/PEAR.php:${PORTSDIR}/devel/pear \
${PEARDIR}/.channels/pear.twig-project.org.reg:${PORTSDIR}/devel/pear-channel-twig
RUN_DEPENDS=	${PEARDIR}/PEAR.php:${PORTSDIR}/devel/pear \
${PEARDIR}/.channels/pear.twig-project.org.reg:${PORTSDIR}/devel/pear-channel-twig


.include <bsd.port.pre.mk>
.include "${PORTSDIR}/devel/pear/bsd.pear.mk"
.include <bsd.port.post.mk>

