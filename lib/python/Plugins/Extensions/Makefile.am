installdir = $(pkglibdir)/python/Plugins/Extensions

SUBDIRS = TuxboxPlugins PicturePlayer MediaScanner SocketMMI 

if HAVE_LIBDDVD
SUBDIRS += DVDPlayer
endif

if VUSOLO4K
SUBDIRS += MiniTV
endif

install_PYTHON =	\
	__init__.py
