ACLOCAL_AMFLAGS = -I m4

SUBDIRS = src doc

.PHONY: ChangeLog
ChangeLog:
	git log --no-merges master | \
		unexpand -a | sed -e 's/\s\s*$$//' > $@
