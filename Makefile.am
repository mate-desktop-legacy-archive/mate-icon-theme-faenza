EXTRA_DIST=AUTHORS COPYING

dist-hook:
	cp -raf matefaenza $(distdir)/matefaenza

uninstall-hook:
	rm -rf $(DESTDIR)$(datadir)/icons/matefaenza

install-data-hook:
	$(mkdir_p) $(DESTDIR)$(datadir)/icons
	cp -raf --no-preserve=ownership matefaenza $(DESTDIR)$(datadir)/icons
