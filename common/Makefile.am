AM_CFLAGS = $(GLOBAL_CFLAGS)

noinst_LTLIBRARIES = libinternalcommon.la

libinternalcommon_la_LIBADD =
libinternalcommon_la_SOURCES =			\
	socket.c				\
	collection.c				\
	socket.h				\
	collection.h

if WIN32
libinternalcommon_la_LIBADD += -lws2_32
endif
