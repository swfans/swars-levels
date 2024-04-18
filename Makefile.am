ACLOCAL_AMFLAGS = --install -I m4

levels_DATA = $(wildcard $(top_srcdir)/LEVELS/C*L*.D*)
levelsdir = $(prefix)/opt/$(PARENT_PACKAGE)/LEVELS

maps_DATA = $(wildcard $(top_srcdir)/MAPS/MAP*.MAD $(top_srcdir)/MAPS/MAP*.B&B)
mapsdir = $(prefix)/opt/$(PARENT_PACKAGE)/MAPS

docs_DATA = levels_config.h
docsdir = $(prefix)/opt/$(PARENT_PACKAGE)

EXTRA_DIST = levels maps docs
