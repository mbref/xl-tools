ACLOCAL_AMFLAGS = -I m4

SUBDIRS = src doc

dist-hook: ChangeLog

ChangeLog: configure.ac
	git log --no-merges master | \
		unexpand -a | sed -e 's/\s\s*$$//' > $@
