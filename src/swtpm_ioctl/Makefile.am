#
# src/cuse_tpm_ioctl/Makefile.am
#
# For the license, see the LICENSE file in the root directory.
#

AM_CFLAGS = @AM_CFLAGS@
AM_LDFLAGS = @AM_LDFLAGS@

noinst_HEADERS =

bin_PROGRAMS = \
	swtpm_ioctl

swtpm_ioctl_SOURCES = tpm_ioctl.c

swtpm_ioctl_CFLAGS = \
	-I$(top_builddir)/include \
	-I$(top_srcdir)/include \
	$(AM_CFLAGS) \
	$(HARDENING_CFLAGS)

swtpm_ioctl_LDFLAGS = \
	$(AM_LDFLAGS)
	$(HARDENING_LDFLAGS)

EXTRA_DIST = \
	README

CLEANFILES = *.gcno *.gcda *.gcov
