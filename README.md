# HOWTO

It is somewhat messy ATM.  Some materials come from datalad.org, so it is
included as submodule which also has its own submodules to operate correctly,
so

      git submodule init
      git submodule update
      cd datalad.org
      git submodule init
      git submodule update -r

# To build brochure

      cd brochure
	  make pics
	  make
