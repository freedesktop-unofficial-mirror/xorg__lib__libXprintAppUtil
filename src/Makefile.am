lib_LTLIBRARIES = libXprintAppUtil.la

libXprintAppUtil_la_SOURCES = \ 
         xpapputil.c

INCLUDES = -I$(top_srcdir)/include/X11/XprintAppUtil


libXprintAppUtil_la_LIBADD = @DEP_LIBS@

libXprintAppUtil_la_LDFLAGS = -version-info 7:0:0 -no-undefined


libXprintAppUtilincludedir = $(includedir)/X11/XprintAppUtil
libXprintAppUtilinclude_HEADERS = \
    $(top_srcdir)/include/X11/XprintAppUtil/xpapputil.h

