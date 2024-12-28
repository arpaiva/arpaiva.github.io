# GTML generated makefile, usable with GNU make.

# commands
GTML = ./gtml
RM   = rm

.SUFFIXES: .gtp .gtm .gtml .html
.PHONY: all clean move

GTML_PROJ_FILE = mySite.gtp

##################### Main output files ########################

OUTPUT_FILES = \
	index.html \
	pubs.html \
	bio.html

##################### Processsing rules ######################

all:
	$(GTML) $(GTML_PROJ_FILE)

clean:
	-$(RM) -fv $(OUTPUT_FILES)
	-$(RM) -fv *~

move: $(OUTPUT_FILES)
	mv -iv $(OUTPUT_FILES) ../

