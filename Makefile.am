SUBDIRS = fmatvec

DIST_SUBDIRS = fmatvec doc

#bin_SCRIPTS = fmatvec-config

pkgconfigdir = $(libdir)/pkgconfig
pkgconfig_DATA = fmatvec.pc

# wrapper target for doxygen in dir doc
.PHONY: doc clean-doc install-doc uninstall-doc

doc:
	(cd doc && $(MAKE) $(AM_MAKEFLAGS) all)

clean-doc:
	(cd doc && $(MAKE) $(AM_MAKEFLAGS) clean)

install-doc:
	(cd doc && $(MAKE) $(AM_MAKEFLAGS) install)

uninstall-doc:
	(cd doc && $(MAKE) $(AM_MAKEFLAGS) uninstall)
