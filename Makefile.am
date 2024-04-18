ACLOCAL_AMFLAGS = --install -I m4

levels_DATA = $(wildcard $(top_srcdir)/LEVELS/C*L*.D*)
levelsdir = $(prefix)/$(PARENT_PACKAGE)/LEVELS

maps_DATA = $(wildcard $(top_srcdir)/MAPS/MAP*.MAD $(top_srcdir)/MAPS/MAP*.B&B)
mapsdir = $(prefix)/$(PARENT_PACKAGE)/MAPS

docs_DATA = levels_config.h
docsdir = $(prefix)/$(PARENT_PACKAGE)

EXTRA_DIST = levels maps docs
