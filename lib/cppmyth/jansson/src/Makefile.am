EXTRA_DIST = jansson.def

include_HEADERS = jansson.h jansson_config.h

noinst_LTLIBRARIES = libjansson.la
#lib_LTLIBRARIES = libjansson.la
libjansson_la_SOURCES = \
	dump.c \
	error.c \
	hashtable.c \
	hashtable.h \
	hashtable_seed.c \
	jansson_private.h \
	load.c \
	lookup3.h \
	memory.c \
	pack_unpack.c \
	strbuffer.c \
	strbuffer.h \
	strconv.c \
	utf.c \
	utf.h \
	value.c
libjansson_la_LDFLAGS = \
	-no-undefined \
	-export-symbols-regex '^json_' \
	-version-info 10:0:6
