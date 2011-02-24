bin_SCRIPTS = mkxlblob.sh
CLEANFILES = $(bin_SCRIPTS)

install-exec-hook:
	cd $(DESTDIR)$(bindir) && \
		$(LN_S) mkxlblob.sh $(DESTDIR)$(bindir)/mkxlblob$(EXEEXT)

uninstall-hook:
	rm -f $(DESTDIR)$(bindir)/mkxlblob$(EXEEXT)
