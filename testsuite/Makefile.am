if COND_USE_MPI
SUBDIRS 	= unittests/catch sanitytests
endif

#runtestdir = $(bindir)
#dist_runtest_DATA = music_tests.sh

EXTRA_DIST	= test_old

install-data-hook:
	@INSTALL_PROGRAM@ music_tests $(DESTDIR)$(bindir)
