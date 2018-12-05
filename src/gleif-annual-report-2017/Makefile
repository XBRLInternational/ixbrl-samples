NAME := "gleif-annual-report-2017"
all:	styles.css styles-responsive.css gleif-annual-report-2017.html 

include ../Makefile.common

styles-responsive.css: less/*.less
	lessc --modify-var="responsive=true" less/styles.less > styles-responsive.css

DIST_NAME := $(NAME)

dist: all
	mkdir -p build/$(DIST_NAME)/reports/
	cp -rv fonts/ styles.css $(NAME).html img/ build/$(DIST_NAME)/reports/
	cp -rv gleif-taxonomy-20171231/* build/$(DIST_NAME)
	cd build && zip --exclude \*.sw? -r $(DIST_NAME).zip $(DIST_NAME)

ixbrl: dist
	cp -rv fonts/ styles.css $(NAME).html img/ build/$(DIST_NAME).zip $(TARGET)
	
