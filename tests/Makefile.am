include $(top_srcdir)/glib-tap.mk

LDADD = $(top_builddir)/govf/libgovf.la

AM_CPPFLAGS =							\
	-I$(top_srcdir)						\
	$(LIBGOVF_CFLAGS)					\
	$(NULL)

AM_CFLAGS = -g $(WARN_CFLAGS)

test_programs =	\
	parser			\
	$(NULL)

dist_test_data =				\
	Fedora_23.ova				\
	Fedora_23.ovf				\
	$(NULL)

-include $(top_srcdir)/git.mk
