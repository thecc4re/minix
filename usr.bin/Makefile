# Makefile for usr.bin

.include <bsd.own.mk>

# NetBSD imports
SUBDIR= login indent m4 stat tic sed mkdep uniq seq du man \
	apropos chpass newgrp passwd bzip2 bzip2recover gzip su genassym \
	ldd/elf32 .WAIT ldd

# Non-NetBSD imports
SUBDIR+= ministat

# Minix commands
SUBDIR+= top mkimage

.include <bsd.subdir.mk>
