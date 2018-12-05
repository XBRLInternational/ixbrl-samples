NAME := xii-financial-statements-2018
all:	styles.css $(NAME).html 

include ../Makefile.common

DIST_NAME := $(NAME)

dist: all
	mkdir -p build/$(DIST_NAME)/reports/
	cp -rv fonts/ styles.css $(NAME).html img/ build/$(DIST_NAME)/reports/
	cp -rv xii-taxonomy-20180630/* build/$(DIST_NAME)
	cd build && zip --exclude \*.sw? -r $(DIST_NAME).zip $(DIST_NAME)

ixbrl: dist
	mkdir -p $(TARGET)
	cp -rv fonts/ styles.css $(NAME).html img/ build/$(DIST_NAME).zip $(TARGET)
	
