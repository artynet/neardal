AM_CPPFLAGS = @gio_CFLAGS@ -I$(top_builddir)/lib -I$(top_srcdir)/lib

libexec_PROGRAMS=ncldemo

ncldemo_SOURCES = \
	$(srcdir)/demo.c

ncldemo_LDADD = @gio_LIBS@ -L$(top_builddir)/lib -lneardal -lpthread
