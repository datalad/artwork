# Unfortunately leads to the recursion
#DEPENDS=pics

# So just call 'make pics' first or whenever figures need to be
# regenerated

include LaTeX.mk

.PHONY: pics
pics:
	@$(MAKE) -C ../datalad.org/src/content/pics/
	@$(MAKE) -C ../datalad.org/src/content/pics/ datalad-logo2.pdf borrowed/git-annex-logo.pdf
	@$(MAKE) -C ../pics/ datalad-whiteboard.png

datalad-whiteboard.%:
	$(MAKE) -C ../pics $@
# Can't be used as is since .gitignore would be searched for in this
# directory
# %.pdf: %.svg @$(MAKE) -f ../Makefile $@
