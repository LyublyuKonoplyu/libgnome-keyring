
noinst_LTLIBRARIES = \
	libegg.la

INCLUDES = \
	-I$(top_srcdir) \
	-I$(top_srcdir)/build \
	-I$(top_builddir)

libegg_la_CFLAGS = \
	$(GLIB_CFLAGS) \
	$(DBUS_CFLAGS) \
	$(LIBGCRYPT_CFLAGS)

libegg_la_SOURCES = \
	egg-dbus.c egg-dbus.h \
	egg-dh.c egg-dh.h \
	egg-hkdf.c egg-hkdf.h \
	egg-libgcrypt.c egg-libgcrypt.h \
	egg-secure-memory.c egg-secure-memory.h \
	egg-testing.c egg-testing.h

CLEANFILES = \
	*.gcda *.gcno

# -------------------------------------------------------------------

SUBDIRS = . tests
