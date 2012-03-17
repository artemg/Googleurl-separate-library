SUBDIRS = . include
lib_LTLIBRARIES = libgoogleurl.la
libgoogleurl_la_SOURCES = include/googleurl/base/string16.cc gurl.cc url_canon_fileurl.cc url_canon_icu.cc url_canon_ip.cc url_canon_path.cc url_canon_query.cc url_canon_stdurl.cc url_parse.cc url_canon_etc.cc url_canon_host.cc url_canon_internal.cc url_canon_mailtourl.cc url_canon_pathurl.cc url_canon_relative.cc url_parse_file.cc url_util.cc include/googleurl/gurl.h include/googleurl/url_canon.h include/googleurl/url_canon_icu.h include/googleurl/url_canon_internal_file.h include/googleurl/url_canon_internal.h include/googleurl/url_canon_ip.h include/googleurl/url_canon_stdstring.h include/googleurl/url_common.h include/googleurl/url_file.h include/googleurl/url_parse.h include/googleurl/url_parse_internal.h include/googleurl/url_util.h
libgoogleurl_la_CPPFLAGS = $(DEPS_CFLAGS)  -I .. -I include/ -DNDEBUG
libgoogleurl_la_LIBADD = $(DEPS_LIBS)

