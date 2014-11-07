# Unfortunately leads to the recursion
#DEPENDS=pics

# So just call 'make pics' first or whenever figures need to be
# regenerated

include LaTeX.mk

.PHONY: pics
pics:
	@$(MAKE) -C ../../data/src/content/pics logo1.pdf

# Can't be used as is since .gitignore would be searched for in this
# directory
# %.pdf: %.svg @$(MAKE) -f ../Makefile $@
