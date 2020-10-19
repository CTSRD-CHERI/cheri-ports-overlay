# llvm-morello

LLVM_SUFFIX=	-morello

COMMENT=	LLVM and Clang with support the Arm Morello architecture

LLVM_MAJOR=	11
SNAPDATE=	20201019

DISTINFO_FILE=	${.CURDIR}/distinfo
DESCR=		${.CURDIR}/pkg-descr
PLIST=		${.CURDIR}/pkg-plist

USE_GITLAB=	yes
GL_SITE=	https://git.morello-project.org
GL_ACCOUNT=	morello
GL_PROJECT=	llvm-project
GL_COMMIT=	5b8db1e2b4140d29c3fe0462471d82e5a90d8018

# Regularly tested targets as part of Android development
LLVM_TARGETS=	AArch64;ARM;BPF;X86

#MASTERDIR=	${.CURDIR}/../llvm-cheri
MASTERDIR=	${PORTSDIR}/devel/llvm-cheri

.include "${MASTERDIR}/Makefile"
