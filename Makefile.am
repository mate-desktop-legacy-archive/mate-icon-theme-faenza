EXTRA_DIST=AUTHORS COPYING

dist-hook:
	cp -raf matefaenza $(distdir)/matefaenza
	cp -raf matefaenzadark $(distdir)/matefaenzadark
	cp -raf matefaenzagray $(distdir)/matefaenzagray

uninstall-hook:
	rm -rf $(DESTDIR)$(datadir)/icons/matefaenza
	rm -rf $(DESTDIR)$(datadir)/icons/matefaenzadark
	rm -rf $(DESTDIR)$(datadir)/icons/matefaenzagray

install-data-hook:
	$(mkdir_p) $(DESTDIR)$(datadir)/icons
	cp -raf --no-preserve=ownership matefaenza $(DESTDIR)$(datadir)/icons
	cp -raf --no-preserve=ownership matefaenzadark $(DESTDIR)$(datadir)/icons
	cp -raf --no-preserve=ownership matefaenzagray $(DESTDIR)$(datadir)/icons
