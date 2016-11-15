libexec_PROGRAMS = nm-openconnect-auth-dialog
libexec_SCRIPTS = nm-openconnect-auth-firefox

nm_openconnect_auth_dialog_CPPFLAGS = \
	$(LIBNM_CFLAGS) \
	$(GLIB_CFLAGS) \
	$(GTK_CFLAGS) \
	$(GCR_CFLAGS) \
	$(OPENCONNECT_CFLAGS) \
	$(LIBXML_CFLAGS) \
	$(LIBSECRET_CFLAGS) \
	-DICONDIR=\""$(datadir)/pixmaps"\" \
	-DBINDIR=\""$(bindir)"\" \
	-DLIBEXECDIR=\""$(libexecdir)"\" \
	-DGNOMELOCALEDIR=\"$(datadir)/locale\" \
	-I"$(top_srcdir)/shared" \
	$(NULL)

nm_openconnect_auth_dialog_SOURCES = \
	main.c \
	$(NULL)

nm_openconnect_auth_dialog_LDADD = \
	$(GTK_LIBS) \
	$(GCR_LIBS) \
	$(LIBNM_LIBS) \
	$(OPENCONNECT_LIBS) \
	$(LIBXML_LIBS) \
	$(LIBSECRET_LIBS)

CLEANFILES = *~

