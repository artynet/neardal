AM_CPPFLAGS = @gio_CFLAGS@ -I$(top_builddir)/lib -I$(top_srcdir)/lib

libexec_PROGRAMS = ncl

ncl_SOURCES = \
	$(srcdir)/ncl.c $(srcdir)/ncl.h \
	$(srcdir)/ncl_cmd.c $(srcdir)/ncl_cmd.h

ncl_LDADD = @gio_LIBS@ -L$(top_builddir)/lib -lneardal
