plugin_LTLIBRARIES = libgstdirectdrawsink.la

libgstdirectdrawsink_la_SOURCES =  gstdirectdrawsink.c gstdirectdrawplugin.c
libgstdirectdrawsink_la_CFLAGS = $(GST_CFLAGS) $(GST_BASE_CFLAGS) \
	$(GST_PLUGINS_BASE_CFLAGS) $(DIRECTX_CFLAGS)
libgstdirectdrawsink_la_LIBADD = $(DIRECTDRAW_LIBS) \
	$(GST_BASE_LIBS) $(GST_PLUGINS_BASE_LIBS) -lgstvideo-$(GST_API_VERSION) \
	-lgstinterfaces-$(GST_API_VERSION)
libgstdirectdrawsink_la_LDFLAGS = $(GST_PLUGIN_LDFLAGS) $(DIRECTX_LDFLAGS)
libgstdirectdrawsink_la_LIBTOOLFLAGS = $(GST_PLUGIN_LIBTOOLFLAGS)

noinst_HEADERS= gstdirectdrawsink.h
