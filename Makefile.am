EXTRA_DIST=AUTHORS COPYING

dist-hook:
	cp -raf matefaenza $(distdir)/matefaenza
	cp -raf matefaenzadark $(distdir)/matefaenzadark

uninstall-hook:
	rm -rf $(DESTDIR)$(datadir)/icons/matefaenza
	rm -rf $(DESTDIR)$(datadir)/icons/matefaenzadark

install-data-hook:
	$(mkdir_p) $(DESTDIR)$(datadir)/icons
	cp -raf --no-preserve=ownership matefaenza $(DESTDIR)$(datadir)/icons
	cp -raf --no-preserve=ownership matefaenzadark $(DESTDIR)$(datadir)/icons
