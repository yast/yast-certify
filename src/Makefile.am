#
# Makefile.am for certify/src
#
# $Id$
#

yncludedir = @yncludedir@/certify

client_DATA =			\
	certify.ycp

ynclude_DATA =			\
	helps.ycp		\
	ui.ycp			\
	ui_system.ycp		\
	ui_tests.ycp

desktop_DATA =			\
	certify.desktop

module_DATA =			\
	Certify.ycp

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA) $(desktop_DATA)

YCPCFLAGS = -I.

ycpchook = certify

certify:
	ln -s . certify

include $(top_srcdir)/Makefile.am.common
